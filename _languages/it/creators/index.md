---
layout: default
lang: it
permalink: /it/creators/
title: "Pensato per i creatori."
description: "Swiftian è una piattaforma orientata alla comunità dove i creatori possono crescere, condividere e innovare insieme."
keywords: "Swiftian, creatori, comunità di coding, collaborazione"
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