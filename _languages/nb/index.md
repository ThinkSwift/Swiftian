---
layout: default
lang: nb
permalink: /nb/
title: "Think Swift."
description: "Start din kreative programmeringsreise med Swiftian – en interaktiv og nøye kuratert plattform for å lære Swift effektivt."
keywords: "Swiftian, Swift, lær programmering, mobilutvikling, lære Swift"
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