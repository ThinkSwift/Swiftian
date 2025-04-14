---
layout: default
lang: pl
permalink: /pl/universe/
title: "Zbuduj swój własny wszechświat."
description: "Poznaj programowanie przez wciągającą opowieść. Nasza historia sci-fi Mars Rebels sprawia, że nauka staje się zabawna i interaktywna."
keywords: "Mars Rebels, opowiadanie historii, kreatywne kodowanie, Swift"
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