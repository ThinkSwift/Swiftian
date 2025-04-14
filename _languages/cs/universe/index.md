---
layout: default
lang: cs
permalink: /cs/universe/
title: "Vytvoř si svůj vlastní vesmír."
description: "Poznejte programování prostřednictvím poutavého vyprávění. Náš sci-fi příběh Mars Rebels dělá výuku zábavnou a interaktivní."
keywords: "Mars Rebels, vyprávění příběhů, kreativní kódování, Swift"
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