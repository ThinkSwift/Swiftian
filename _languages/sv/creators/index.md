---
layout: default
lang: sv
permalink: /sv/creators/
title: "Skapat för skapare."
description: "Swiftian är en gemenskapsdriven plattform där skapare kan växa, dela och skapa innovation tillsammans."
keywords: "Swiftian, skapare, kodningsgemenskap, samarbete"
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