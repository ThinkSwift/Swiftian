---
layout: default
lang: fi
permalink: /fi/universe/
title: "Rakenna oma universumisi."
description: "Tutustu ohjelmointiin tarinankerronnan kautta. Tieteistarina Mars Rebels tekee oppimisesta hauskaa ja mukaansatempaavaa."
keywords: "Mars Rebels, tarinallinen oppiminen, luova koodaus, Swift"
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