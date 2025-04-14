---
layout: default
lang: zh-hant
permalink: /zh-hant/coding/
title: "創造。探索。"
description: "透過精心設計的互動課程學習 Swift。從簡單開始，逐步掌握程式設計技能，實現你的大計劃。"
keywords: "Swift, Swiftian, 學習 Swift, 程式課程, iOS 開發"
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