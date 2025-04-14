---
layout: default
lang: sk
permalink: /sk/universe/
title: "Vytvor si vlastný vesmír."
description: "Objav programovanie cez pútavé rozprávanie príbehov. Naša sci-fi séria Mars Rebels robí učenie zábavným a interaktívnym."
keywords: "Mars Rebels, rozprávanie príbehov, kreatívne programovanie, Swift"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].universe %}
{% assign media = site.data.media.universe %}

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

---

#### [← {{ nav.coding }}]({{ prefix }}/coding/) | [{{ nav.groove }} →]({{ prefix }}/groove/)