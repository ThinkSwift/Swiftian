---
layout: default
lang: cs
permalink: /cs/creators/
title: "Pro tvůrce."
description: "Swiftian je platforma zaměřená na komunitu, která podporuje růst, sdílení a inovace mezi tvůrci."
keywords: "Swiftian, tvůrci, programovací komunita, spolupráce"
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