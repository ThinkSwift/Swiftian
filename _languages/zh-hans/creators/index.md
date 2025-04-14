---
layout: default
lang: zh-hans
permalink: /zh-hans/creators/
title: "为创作者而生。"
description: "Swiftian 是一个为创作者而建的平台，鼓励共同学习、分享与创新。"
keywords: "Swiftian, 创作者, 编程社区, 协作"
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