---
layout: default
lang: ja
permalink: /ja/
title: "Think Swift."
description: "Swiftian で創造的なプログラミングの旅を始めよう。Swift を効率よく学べるインタラクティブで厳選されたプラットフォームです。"
keywords: "Swiftian, Swift, プログラミング学習, モバイル開発, Swift を学ぶ"
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