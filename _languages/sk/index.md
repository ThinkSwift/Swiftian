---
layout: default
lang: sk
permalink: /sk/
title: "Think Swift."
description: "Začni svoju kreatívnu cestu programovaním so Swiftian – interaktívnou a starostlivo navrhnutou platformou na učenie sa jazyka Swift."
keywords: "Swiftian, Swift, nauč sa programovať, vývoj mobilných aplikácií, učenie Swift"
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