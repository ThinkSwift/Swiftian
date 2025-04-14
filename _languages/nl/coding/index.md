---
layout: default
lang: nl
permalink: /nl/coding/
title: "Creëer. Ontdek."
description: "Leer Swift via interactieve, gestructureerde lessen. Begin klein, denk groots en ontwikkel je codeervaardigheden stap voor stap."
keywords: "Swift, Swiftian, Swift leren, programmeercursus, coderen"
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