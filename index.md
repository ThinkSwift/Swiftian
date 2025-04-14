---
layout: default
lang: en
permalink: /
title: "Think Swift."
description: "Make something new. Push boundaries. Swiftian is a curated, interactive platform for learning Swift creatively."
keywords: "Swiftian, Swift, coding, learn Swift, mobile development"
---
{% include locale.liquid %}
{% assign content = site.data.pages[lang].home %}

# {{ content.title }}

{% include video.html src="/assets/videos/logo.mp4" id="logoVideo" soundIconId="soundIcon" %}

{{ content.text | newline_to_br }}

- [{{ nav.coding }} {{ arrow_right }}]({{ prefix }}/coding/)
- [{{ nav.universe }} {{ arrow_right }}]({{ prefix }}/universe/)
- [{{ nav.groove }} {{ arrow_right }}]({{ prefix }}/groove/)
- [{{ nav.creators }} {{ arrow_right }}]({{ prefix }}/creators/)

---
{% include footer.html %}
