---
layout: default
lang: it
permalink: /it/universe/
title: "Costruisci il tuo universo."
description: "Scopri la programmazione attraverso lo storytelling coinvolgente. La nostra storia sci-fi Mars Rebels rende l’apprendimento divertente e interattivo."
keywords: "Mars Rebels, storytelling, programmazione creativa, Swift"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].universe %}
{% assign media = site.data.media.universe %}

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

---

#### [← {{ nav.coding }}]({{ prefix }}/coding/) | [{{ nav.groove }} →]({{ prefix }}/groove/)