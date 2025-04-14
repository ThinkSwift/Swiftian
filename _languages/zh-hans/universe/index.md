---
layout: default
lang: zh-hans
permalink: /zh-hans/universe/
title: "打造你的宇宙。"
description: "用沉浸式故事方式学习编程。我们的科幻故事 Mars Rebels 让编程变得更有趣、更具互动性。"
keywords: "Mars Rebels, 编程故事, 创意编程, Swift"
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