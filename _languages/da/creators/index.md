---
layout: default
lang: da
permalink: /da/creators/
title: "Skabt til skabere."
description: "Swiftian er en fællesskabsbaseret platform for skabere til at vokse, dele og innovere sammen."
keywords: "Swiftian, skabere, kodefællesskab, samarbejde"
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