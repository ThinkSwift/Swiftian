---
layout: default
lang: en
permalink: /creators/
title: "Made for Creators."
description: "Swiftian is a community-focused platform built for creators to grow, share, and innovate together."
keywords: "Swiftian, creators, coding community, collaboration"
---

{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [{{ arrow_left }} {{ nav.groove }}]({{ prefix }}/groove/)

# {{ content.title }}

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

#### [{{ arrow_left }} {{ nav.groove }}]({{ prefix }}/groove/)
