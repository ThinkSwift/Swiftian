---
layout: default
lang: ja
permalink: /ja/creators/
title: "クリエイターのために。"
description: "Swiftian は、学び・共有・共に成長することを目指すクリエイターのためのコミュニティ型プラットフォームです。"
keywords: "Swiftian, クリエイター, コーディングコミュニティ, 協働"
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