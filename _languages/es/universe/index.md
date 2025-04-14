---
layout: default
lang: es
permalink: /es/universe/
title: "Construye tu propio universo."
description: "Descubre la programación a través de historias envolventes. Nuestra historia de ciencia ficción, Mars Rebels, hace que aprender sea divertido e interactivo."
keywords: "Mars Rebels, narración interactiva, programación creativa, Swift"
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