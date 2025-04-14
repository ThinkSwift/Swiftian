---
layout: default
lang: fi
permalink: /fi/
title: "Think Swift."
description: "Aloita luova ohjelmointimatkasi Swiftianin avulla – vuorovaikutteinen ja huolella kuratoitu alusta Swiftin oppimiseen."
keywords: "Swiftian, Swift, ohjelmoinnin oppiminen, mobiilikehitys, Swift opetus"
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