---
layout: default
lang: ro
permalink: /ro/groove/
title: "Mișcă-te pe ritm."
description: "Muzică selectată special pentru a îmbunătăți concentrarea și creativitatea în timpul programării. Optimizează-ți fluxul cu ritm."
keywords: "muzică pentru programare, productivitate, creativitate, concentrare, Swiftian"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].groove %}
{% assign media = site.data.media.groove %}

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
  type=media.preview.type
  src=media.preview.src
  max=media.preview.max
  controls=media.preview.controls
%}

---

#### [← {{ nav.universe }}]({{ prefix }}/universe/) | [{{ nav.creators }} →]({{ prefix }}/creators/)