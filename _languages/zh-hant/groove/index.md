---
layout: default
lang: zh-hant
permalink: /zh-hant/groove/
title: "隨著節奏律動。"
description: "專為提升專注與創造力而設計的音樂精選，讓你的編程體驗更高效、更流暢。"
keywords: "程式音樂, 專注, 創造力, 音樂, Swiftian"
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