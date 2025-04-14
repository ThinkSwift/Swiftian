---
layout: default
lang: da
permalink: /da/
title: "Think Swift."
description: "Start din kreative koderejse med Swiftian – en interaktiv og kurateret platform til at lære Swift på en ny måde."
keywords: "Swiftian, Swift, lær at kode, mobiludvikling, Swift undervisning"
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