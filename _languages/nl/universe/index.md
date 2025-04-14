---
layout: default
lang: nl
permalink: /nl/universe/
title: "Bouw je eigen universum."
description: "Ontdek programmeren via meeslepende verhalen. Mars Rebels, ons sci-fi avontuur, maakt leren leuk en interactief."
keywords: "Mars Rebels, verhalen vertellen, creatieve codering, Swift"
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