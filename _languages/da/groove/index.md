---
layout: default
lang: da
permalink: /da/groove/
title: "Bevæg dig til rytmen."
description: "Udvalgt musik designet til at forbedre fokus og kreativitet, mens du koder. Få mere ud af din flowtilstand med rytme."
keywords: "kodemusik, produktivitet, fokus, kreativitet, Swiftian"
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