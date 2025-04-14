---
layout: default
lang: hu
permalink: /hu/
title: "Think Swift."
description: "Kezdd el kreatív programozási utazásodat a Swiftian-nel – egy interaktív, gondosan összeállított platform a Swift nyelv elsajátításához."
keywords: "Swiftian, Swift, programozás tanulás, mobilfejlesztés, Swift nyelv"
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