---
layout: default
lang: zh-hans
permalink: /zh-hans/coding/
title: "创造。探索。"
description: "通过精选互动课程学习 Swift。从简单入门，逐步掌握编程技能，实现大梦想。"
keywords: "Swift, Swiftian, 学习 Swift, 编程课程, iOS开发"
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