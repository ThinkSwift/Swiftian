---
layout: default
title: "Think Swift."
description: "Make something new. Push boundaries. Swiftian is a curated, interactive platform for learning Swift creatively."
keywords: "Swiftian, Swift, coding, learn Swift, mobile development"
lang: en
lang: zh-hans
permalink: /zh-hans/
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
