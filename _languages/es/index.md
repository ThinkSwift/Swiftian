---
layout: default
lang: es
permalink: /es/
title: "Think Swift."
description: "Comienza tu viaje creativo en la programación con Swiftian, una plataforma interactiva y cuidadosamente diseñada para aprender Swift de forma efectiva."
keywords: "Swiftian, Swift, aprender a programar, desarrollo móvil, aprender Swift"
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