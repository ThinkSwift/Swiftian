---
layout: default
lang: tr
permalink: /tr/universe/
title: "Kendi evrenini inşa et."
description: "Sürükleyici hikaye anlatımıyla programlamayı keşfedin. Bilim kurgu hikayemiz Mars Rebels, öğrenmeyi eğlenceli ve etkileşimli hale getiriyor."
keywords: "Mars Rebels, hikaye anlatımı, yaratıcı kodlama, Swift"
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