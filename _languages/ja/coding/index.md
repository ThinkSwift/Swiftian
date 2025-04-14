---
layout: default
lang: ja
permalink: /ja/coding/
title: "創造しよう。探求しよう。"
description: "構造的で対話的なレッスンを通じて Swift を学びます。小さく始めて、大きく考え、一歩ずつスキルを高めましょう。"
keywords: "Swift, Swiftian, Swift 学習, プログラミング講座, コーディング"
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