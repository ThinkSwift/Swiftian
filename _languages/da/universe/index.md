---
layout: default
lang: da
permalink: /da/universe/
title: "Byg dit eget univers."
description: "Oplev kodning gennem historier. Sci-fi fortællingen Mars Rebels gør læring sjov, kreativ og engagerende."
keywords: "Mars Rebels, historiefortælling, kreativ kodning, Swift"
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