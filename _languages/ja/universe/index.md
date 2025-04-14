---
layout: default
lang: ja
permalink: /ja/universe/
title: "自分だけの世界を作ろう。"
description: "没入感のあるストーリーテリングでプログラミングを学ぼう。SF 物語 Mars Rebels が、学習を楽しく、インタラクティブにします。"
keywords: "Mars Rebels, ストーリーテリング, クリエイティブコーディング, Swift"
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