---
layout: default
lang: ro
permalink: /ro/creators/
title: "Creat pentru creatori."
description: "Swiftian este o platformă orientată spre comunitate unde creatorii pot învăța, colabora și inova împreună."
keywords: "Swiftian, creatori, comunitate de programatori, colaborare"
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