---
layout: default
lang: tr
permalink: /tr/creators/
title: "Yaratıcılar için tasarlandı."
description: "Swiftian, yaratıcıların birlikte öğrenip, paylaşabileceği ve yenilikler üretebileceği topluluk odaklı bir platformdur."
keywords: "Swiftian, yaratıcılar, programlama topluluğu, işbirliği"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [← {{ nav.home }}]({{ prefix }}/)

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