---
layout: default
lang: nl
permalink: /nl/
title: "Think Swift."
description: "Begin je creatieve programmeerreis met Swiftian – een interactieve en zorgvuldig samengestelde leeromgeving voor Swift."
keywords: "Swiftian, Swift, leren programmeren, mobiele ontwikkeling, Swift leren"
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