---
layout: default
lang: fr
permalink: /fr/universe/
title: "Construisez votre univers."
description: "Découvrez la programmation à travers des récits immersifs. Mars Rebels, notre histoire de science-fiction, rend l’apprentissage ludique et interactif."
keywords: "Mars Rebels, narration, codage créatif, Swift"
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