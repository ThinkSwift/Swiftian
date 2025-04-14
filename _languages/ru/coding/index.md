---
layout: default
lang: ru
permalink: /ru/coding/
title: "Создавай. Исследуй."
description: "Изучай Swift с помощью интерактивных и структурированных уроков. Начни с малого, мысли масштабно и развивай навыки шаг за шагом."
keywords: "Swift, Swiftian, изучение Swift, курс программирования, кодинг"
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