---
layout: default
lang: da
permalink: /da/coding/
title: "Skab. Udforsk."
description: "Lær Swift gennem interaktive og strukturerede lektioner. Start i det små og opbyg dine kodningsfærdigheder trin for trin."
keywords: "Swift, Swiftian, kodning, lær Swift, programmeringskurser"
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