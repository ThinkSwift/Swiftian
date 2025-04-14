---
layout: default
lang: en
permalink: /
title: "{{ meta.title }}"
description: "{{ meta.description }}"
keywords: "{{ meta.keywords }}"
---
{% include locale.liquid %}

# Swiftian

{% include video.html src="/assets/videos/logo.mp4" id="logoVideo" soundIconId="soundIcon" %}

{{ nav.tagline1 }}  
{{ nav.tagline2 }}

- [{{ nav.coding }} →]({{ prefix }}/coding/)
- [{{ nav.universe }} →]({{ prefix }}/universe/)
- [{{ nav.groove }} →]({{ prefix }}/groove/)
- [{{ nav.creators }} →]({{ prefix }}/creators/)

---
{% include footer.html %}
