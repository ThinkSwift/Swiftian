---
layout: default
lang: zh-hans
permalink: /zh-hans/groove/
title: "跟着节奏动起来。"
description: "专为编程效率与创意集中打造的精选音乐，提升你的专注力与工作节奏。"
keywords: "编程音乐, 专注, 创造力, 音乐, Swiftian"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].groove %}
{% assign media = site.data.media.groove %}

#### [← {{ nav.home }}]({{ prefix }}/)

# {{ content.title }}

{% if content.spotify_id %}
<iframe
  data-testid="embed-iframe"
  style="border-radius:12px"
  src="https://open.spotify.com/embed/album/{{ content.spotify_id }}?utm_source=generator&theme=0"
  width="100%"
  height="352"
  frameBorder="0"
  allowfullscreen=""
  allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
  loading="lazy">
</iframe>
{% endif %}

{% for section in content.sections %}
### {{ section.heading }}
{{ section.text }}

{% endfor %}

{% include media.html
  type=media.preview.type
  src=media.preview.src
  max=media.preview.max
  controls=media.preview.controls
%}

---

#### [← {{ nav.universe }}]({{ prefix }}/universe/) | [{{ nav.creators }} →]({{ prefix }}/creators/)