---
layout: default
lang: ro
permalink: /ro/coding/
title: "Creează. Explorează."
description: "Învață Swift prin lecții interactive și bine structurate. Începe de la bază, gândește la scară mare și dezvoltă-ți abilitățile pas cu pas."
keywords: "Swift, Swiftian, curs de programare, învățare Swift, codare"
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