---
layout: default
lang: ro
permalink: /ro/universe/
title: "Construiește-ți propriul univers."
description: "Descoperă programarea prin povești captivante. Povestea noastră SF, Mars Rebels, face învățarea mai distractivă și interactivă."
keywords: "Mars Rebels, storytelling, programare creativă, Swift"
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