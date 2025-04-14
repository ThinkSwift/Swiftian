---
layout: default
lang: ko
permalink: /ko/coding/
title: "창조하고, 탐험하세요."
description: "구성된 단계별 인터랙티브 강의를 통해 Swift를 배워보세요. 작게 시작하고, 크게 생각하며 실력을 차근차근 키워나갈 수 있습니다."
keywords: "Swift, Swiftian, Swift 배우기, 코딩 강의, 프로그래밍 입문"
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