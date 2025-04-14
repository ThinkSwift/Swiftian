---
layout: default
lang: en
permalink: /universe/
title: "Build Your Universe."
description: "Discover coding through immersive storytelling. Mars Rebels, our sci-fi narrative, makes coding engaging, interactive, and enjoyable."
keywords: "Mars Rebels, storytelling, creative coding, Swift"
---

{% include locale.liquid %}
{% assign content = site.data.pages[lang].universe %}
{% assign media = site.data.media.universe %}

#### [{{ arrow_left }} {{ nav.home }}]({{ prefix }}/)

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

#### [{{ arrow_left }} {{ nav.coding }}]({{ prefix }}/coding/) | [{{ nav.groove }} {{ arrow_right }}]({{ prefix }}/groove/)
