---
layout: default
lang: id
permalink: /id/universe/
title: "Bangun alam semesta Anda sendiri."
description: "Pelajari coding melalui storytelling yang imersif. Kisah fiksi ilmiah Mars Rebels menjadikan pembelajaran menyenangkan dan interaktif."
keywords: "Mars Rebels, storytelling, coding kreatif, Swift"
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