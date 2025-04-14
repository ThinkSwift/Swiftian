---
layout: default
lang: en
permalink: /
title: "{{ meta.title }}"
description: "{{ meta.description }}"
keywords: "{{ meta.keywords }}"
---
{% include locale.liquid %}
{% assign content = site.data.pages.home[lang] %}

# {{ content.title }}

{% include video.html src="/assets/videos/logo.mp4" id="logoVideo" soundIconId="soundIcon" %}

{{ content.text | newline_to_br }}

- [{{ nav.coding }} →]({{ prefix }}/coding/)
- [{{ nav.universe }} →]({{ prefix }}/universe/)
- [{{ nav.groove }} →]({{ prefix }}/groove/)
- [{{ nav.creators }} →]({{ prefix }}/creators/)

---
{% include footer.html %}
