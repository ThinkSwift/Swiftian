---
layout: default
lang: ko
permalink: /ko/universe/
title: "당신만의 세계를 만들어보세요."
description: "몰입감 있는 스토리텔링을 통해 코딩을 배우세요. SF 기반 이야기 Mars Rebels는 학습을 더욱 재미있고 인터랙티브하게 만들어줍니다."
keywords: "Mars Rebels, 스토리텔링, 창의적 코딩, Swift"
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