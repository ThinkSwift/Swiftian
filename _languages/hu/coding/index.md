---
layout: default
lang: hu
permalink: /hu/coding/
title: "Alkoss. Fedezz fel."
description: "Tanulj meg Swiftet interaktív, jól felépített leckéken keresztül. Kezdj kicsiben, gondolkodj nagyban, fejlődj lépésről lépésre."
keywords: "Swift, Swiftian, Swift tanulás, programozási kurzus, kódolás"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].coding %}
{% assign media = site.data.media.coding %}

#### [← {{ nav.home }}]({{ prefix }}/)

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
  type=media.logo.type
  src=media.logo.src
  alt=media.logo.alt
  max=media.logo.max
%}

---

#### [{{ nav.universe }} →]({{ prefix }}/universe/)