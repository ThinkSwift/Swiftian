---
layout: default
lang: uk
permalink: /uk/
title: "Think Swift."
description: "Розпочніть свою творчу подорож у програмуванні зі Swiftian — інтерактивною платформою, розробленою для ефективного вивчення Swift."
keywords: "Swiftian, Swift, вивчення програмування, мобільна розробка, вивчити Swift"
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