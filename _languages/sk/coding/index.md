---
layout: default
lang: sk
permalink: /sk/coding/
title: "Tvor. Objavuj."
description: "Nauč sa Swift pomocou interaktívnych a štruktúrovaných lekcií. Začni jednoducho, mysli vo veľkom a rozvíjaj sa krok za krokom."
keywords: "Swift, Swiftian, učenie Swift, programovací kurz, kódovanie"
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