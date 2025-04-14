---
layout: default
lang: sv
permalink: /sv/
title: "Think Swift."
description: "Starta din kreativa kodningsresa med Swiftian – en interaktiv och noggrant utformad plattform för att lära dig Swift effektivt."
keywords: "Swiftian, Swift, lära sig programmera, mobilutveckling, lära sig Swift"
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