---
layout: default
lang: zh-hant
permalink: /zh-hant/universe/
title: "打造你的宇宙。"
description: "透過沉浸式故事學習程式設計。科幻故事 Mars Rebels 讓學習變得更有趣、更具互動性。"
keywords: "Mars Rebels, 程式故事, 創意編程, Swift"
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