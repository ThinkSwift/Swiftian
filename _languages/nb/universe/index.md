---
layout: default
lang: nb
permalink: /nb/universe/
title: "Bygg ditt eget univers."
description: "Utforsk programmering gjennom fengende historiefortelling. Vår sci-fi-fortelling Mars Rebels gjør læring engasjerende og interaktivt."
keywords: "Mars Rebels, historiefortelling, kreativ koding, Swift"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].universe %}
{% assign media = site.data.media.universe %}

#### [← {{ nav.home }}]({{ prefix }}/)

# {{ content.title }}

{% include media.html
  type=media.header.type
  src=media.header.src
  alt=media.header.alt
  max=media.header.max
%}

{% for section in content.sections %}
### {{ section.heading }}
{{ section.text }}

{% endfor %}

---

#### [← {{ nav.coding }}]({{ prefix }}/coding/) | [{{ nav.groove }} →]({{ prefix }}/groove/)