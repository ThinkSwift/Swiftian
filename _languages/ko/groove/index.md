---
layout: default
lang: ko
permalink: /ko/groove/
title: "비트에 맞춰 움직이세요."
description: "코딩 중 집중력과 창의력을 높여주는 엄선된 음악. 리듬을 통해 더욱 몰입도 높은 작업 환경을 경험하세요."
keywords: "코딩 음악, 생산성, 창의력, 집중, Swiftian"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].groove %}
{% assign media = site.data.media.groove %}

#### [← {{ nav.universe }}]({{ prefix }}/universe/)

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
  type=media.preview.type
  src=media.preview.src
  max=media.preview.max
  controls=media.preview.controls
%}

---

#### [← {{ nav.universe }}]({{ prefix }}/universe/) | [{{ nav.creators }} →]({{ prefix }}/creators/)