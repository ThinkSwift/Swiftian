---
layout: default
lang: sv
permalink: /sv/universe/
title: "Bygg ditt eget universum."
description: "Utforska programmering genom fängslande berättelser. Vår sci-fi-historia Mars Rebels gör lärandet roligt och interaktivt."
keywords: "Mars Rebels, berättande, kreativ kodning, Swift"
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