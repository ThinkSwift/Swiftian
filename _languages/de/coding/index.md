---
layout: default
lang: de
permalink: /de/coding/
title: "Erstellen. Entdecken."
description: "Lerne Swift durch strukturierte, interaktive Lektionen. Starte klein, denke groß und entwickle deine Coding-Fähigkeiten Schritt für Schritt."
keywords: "Swift, Swiftian, Swift lernen, Programmierkurs, Coding"
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