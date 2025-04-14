---
layout: default
lang: hu
permalink: /hu/creators/
title: "Alkotóknak készült."
description: "A Swiftian egy közösségi platform, amely lehetőséget ad az alkotóknak a tanulásra, megosztásra és az együttműködésre."
keywords: "Swiftian, alkotók, programozói közösség, együttműködés"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [← {{ nav.groove }}]({{ prefix }}/groove/)

# {{ content.title }}

{% for section in content.sections %}
### {{ section.heading }}
{{ section.text }}

{% endfor %}

{% include media.html
  type=media.logo.type
  src=media.logo.src
  alt=media.logo.alt
  max=media.logo.max
%}

---

#### [← {{ nav.groove }}]({{ prefix }}/groove/)