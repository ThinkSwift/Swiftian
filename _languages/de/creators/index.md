---
layout: default
lang: de
permalink: /de/creators/
title: "Für Kreative gemacht."
description: "Swiftian ist eine community-orientierte Plattform, auf der Kreative gemeinsam lernen, teilen und Innovationen schaffen."
keywords: "Swiftian, Kreative, Programmier-Community, Zusammenarbeit"
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