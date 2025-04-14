---
layout: default
lang: es
permalink: /es/coding/
title: "Crea. Explora."
description: "Aprende Swift a través de lecciones interactivas y estructuradas. Empieza con lo básico, piensa en grande y mejora paso a paso."
keywords: "Swift, Swiftian, aprender Swift, curso de programación, codificación"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].coding %}
{% assign media = site.data.media.coding %}

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

{% include media.html
  type=media.logo.type
  src=media.logo.src
  alt=media.logo.alt
  max=media.logo.max
%}

---

#### [{{ nav.universe }} →]({{ prefix }}/universe/)