---
layout: default
lang: de
permalink: /de/universe/
title: "Baue dein eigenes Universum."
description: "Entdecke das Programmieren durch fesselndes Storytelling. Unsere Sci-Fi-Geschichte Mars Rebels macht das Lernen spannend und interaktiv."
keywords: "Mars Rebels, Storytelling, Kreatives Coden, Swift"
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