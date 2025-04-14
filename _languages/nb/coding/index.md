---
layout: default
lang: nb
permalink: /nb/coding/
title: "Skap. Utforsk."
description: "Lær Swift med interaktive og strukturerte leksjoner. Start i det små, tenk stort og utvikle dine ferdigheter steg for steg."
keywords: "Swift, Swiftian, lære Swift, programmeringskurs, koding"
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