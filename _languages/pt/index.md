---
layout: default
lang: pt
permalink: /pt/
title: "Think Swift."
description: "Comece sua jornada criativa na programação com o Swiftian — uma plataforma interativa e cuidadosamente elaborada para aprender Swift com eficácia."
keywords: "Swiftian, Swift, aprender programação, desenvolvimento mobile, aprender Swift"
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