---
layout: default
lang: de
permalink: /de/
title: "Think Swift."
description: "Beginne deine kreative Programmierreise mit Swiftian – einer interaktiven, kuratierten Plattform zum effektiven Lernen von Swift."
keywords: "Swiftian, Swift, Programmieren lernen, Mobile Entwicklung, Swift lernen"
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