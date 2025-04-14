---
layout: default
lang: ko
permalink: /ko/creators/
title: "창작자를 위한 공간입니다."
description: "Swiftian은 창작자들이 함께 배우고, 나누고, 혁신할 수 있도록 돕는 커뮤니티 중심 플랫폼입니다."
keywords: "Swiftian, 창작자, 프로그래밍 커뮤니티, 협업"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [← {{ nav.groove }}]({{ prefix }}/groove/)

# {{ content.title }}

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

#### [← {{ nav.groove }}]({{ prefix }}/groove/)