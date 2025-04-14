---
layout: default
lang: zh-hans
permalink: /zh-hans/
title: "Think Swift."
description: "通过 Swiftian 踏上创意编程之旅。这是一个精选、互动的 Swift 学习平台，帮助你打破边界，创造新可能。"
keywords: "Swiftian, Swift, 编程学习, 移动开发, 学习 Swift"
---

{% include locale.liquid %}
{% assign content = site.data.pages[lang].home %}

# {{ content.title }}

{% include video.html src="/assets/videos/logo.mp4" id="logoVideo" soundIconId="soundIcon" %}

{{ content.text | newline_to_br }}

- [{{ nav.coding }} →]({{ prefix }}/coding/)
- [{{ nav.universe }} →]({{ prefix }}/universe/)
- [{{ nav.groove }} →]({{ prefix }}/groove/)
- [{{ nav.creators }} →]({{ prefix }}/creators/)

---
{% include footer.html %}