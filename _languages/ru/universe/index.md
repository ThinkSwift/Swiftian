---
layout: default
lang: ru
permalink: /ru/universe/
title: "Построй свою вселенную."
description: "Открой для себя программирование через захватывающий сторителлинг. Наша научно-фантастическая история Mars Rebels делает обучение увлекательным и интерактивным."
keywords: "Mars Rebels, сторителлинг, креативное программирование, Swift"
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