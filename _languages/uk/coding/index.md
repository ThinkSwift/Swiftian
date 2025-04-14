---
layout: default
lang: uk
permalink: /uk/coding/
title: "Створюй. Досліджуй."
description: "Вивчайте Swift за допомогою структурованих інтерактивних уроків. Почніть з простого, мисліть масштабно, розвивайтесь крок за кроком."
keywords: "Swift, Swiftian, вивчити Swift, курс програмування, кодування"
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