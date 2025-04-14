---
layout: default
lang: nl
permalink: /nl/creators/
title: "Gemaakt voor makers."
description: "Swiftian is een community-gericht platform waar makers kunnen groeien, delen en samen innoveren."
keywords: "Swiftian, makers, programmeergemeenschap, samenwerking"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [← {{ nav.groove }}]({{ prefix }}/groove/)

# {{ content.title }}

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

#### [← {{ nav.groove }}]({{ prefix }}/groove/)