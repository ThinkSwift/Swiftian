---
layout: default
lang: ja
permalink: /ja/groove/
title: "リズムに乗って動こう。"
description: "コーディング中の集中力と創造力を高めるために選ばれた音楽。仕事の流れをリズムで最適化しましょう。"
keywords: "プログラミング音楽, 生産性, 創造性, 集中力, Swiftian"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].groove %}
{% assign media = site.data.media.groove %}

#### [← {{ nav.universe }}]({{ prefix }}/universe/)

# {{ content.title }}

{% include media.html
  type=media.header.type
  src=media.header.src
  alt=media.header.alt
  max=media.header.max
%}

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