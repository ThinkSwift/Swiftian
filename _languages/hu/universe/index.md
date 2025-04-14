---
layout: default
lang: hu
permalink: /hu/universe/
title: "Építsd fel a saját univerzumod."
description: "Ismerd meg a programozást lebilincselő történeteken keresztül. A sci-fi történetünk, a Mars Rebels, szórakoztatóvá és élvezetessé teszi a tanulást."
keywords: "Mars Rebels, történetmesélés, kreatív programozás, Swift"
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