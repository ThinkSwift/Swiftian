---
layout: default
lang: ro
permalink: /ro/
title: "Think Swift."
description: "Începe-ți călătoria creativă în programare cu Swiftian — o platformă interactivă și atent concepută pentru a învăța Swift eficient."
keywords: "Swiftian, Swift, învață programare, dezvoltare mobilă, învață Swift"
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