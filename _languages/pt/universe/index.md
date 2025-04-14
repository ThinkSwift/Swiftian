---
layout: default
lang: pt
permalink: /pt/universe/
title: "Construa seu próprio universo."
description: "Descubra a programação por meio de narrativas envolventes. Nossa história sci-fi, Mars Rebels, torna o aprendizado divertido e interativo."
keywords: "Mars Rebels, storytelling, codificação criativa, Swift"
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