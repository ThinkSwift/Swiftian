---
layout: default
lang: ru
permalink: /ru/creators/
title: "Создано для создателей."
description: "Swiftian — это платформа, ориентированная на сообщество, где разработчики могут учиться, делиться опытом и совместно создавать инновации."
keywords: "Swiftian, создатели, сообщество программистов, сотрудничество"
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