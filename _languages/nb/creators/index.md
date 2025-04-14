---
layout: default
lang: nb
permalink: /nb/creators/
title: "Laget for skapere."
description: "Swiftian er en fellesskapsdrevet plattform hvor skapere kan vokse, dele og innovere sammen."
keywords: "Swiftian, skapere, kodefellesskap, samarbeid"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [← {{ nav.groove }}]({{ prefix }}/groove/)

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

#### [← {{ nav.groove }}]({{ prefix }}/groove/)