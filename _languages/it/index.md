---
layout: default
lang: it
permalink: /it/
title: "Think Swift."
description: "Inizia il tuo percorso creativo nella programmazione con Swiftian — una piattaforma interattiva e curata per imparare Swift in modo efficace."
keywords: "Swiftian, Swift, imparare a programmare, sviluppo mobile, imparare Swift"
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