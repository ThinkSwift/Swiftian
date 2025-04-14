---
layout: default
lang: ko
permalink: /ko/
title: "Think Swift."
description: "Swiftian과 함께 창의적인 프로그래밍 여정을 시작하세요. Swift 학습을 위한 인터랙티브하고 정교하게 구성된 플랫폼입니다."
keywords: "Swiftian, Swift, 프로그래밍 배우기, 모바일 개발, Swift 학습"
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