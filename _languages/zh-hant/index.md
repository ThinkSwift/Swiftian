---
layout: default
lang: zh-hant
permalink: /zh-hant/
title: "Think Swift."
description: "透過 Swiftian 展開創意編程之旅。這是一個精選互動的 Swift 學習平台，幫助你突破界限，激發創造力。"
keywords: "Swiftian, Swift, 程式學習, 行動開發, 學習 Swift"
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