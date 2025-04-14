---
layout: default
lang: sv
permalink: /sv/coding/
title: "Skapa. Utforska."
description: "Lär dig Swift genom interaktiva och strukturerade lektioner. Börja enkelt, tänk stort och utveckla dina färdigheter steg för steg."
keywords: "Swift, Swiftian, lära Swift, programmeringskurs, kodning"
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