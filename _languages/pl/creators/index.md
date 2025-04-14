---
layout: default
lang: pl
permalink: /pl/creators/
title: "Dla twórców."
description: "Swiftian to platforma społecznościowa stworzona dla twórców, aby wspólnie się uczyć, dzielić i tworzyć innowacje."
keywords: "Swiftian, twórcy, społeczność programistyczna, współpraca"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [← {{ nav.home }}]({{ prefix }}/)

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