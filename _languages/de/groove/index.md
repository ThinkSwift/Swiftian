---
layout: default
lang: de
permalink: /de/groove/
title: "Bewege dich im Takt."
description: "Ausgewählte Musik für Fokus und Kreativität beim Programmieren. Optimiere deinen Workflow mit dem richtigen Rhythmus."
keywords: "Programmiermusik, Produktivität, Kreativität, Musik, Swiftian"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].groove %}
{% assign media = site.data.media.groove %}

#### [← {{ nav.universe }}]({{ prefix }}/universe/)

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