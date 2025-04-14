---
layout: default
lang: ar
permalink: /ar/universe/
title: "ابنِ عالمك الخاص."
description: "استمتع بتعلم البرمجة من خلال السرد القصصي التفاعلي. قصة الخيال العلمي Mars Rebels تجعل التعلم ممتعًا وجذابًا."
keywords: "Mars Rebels, قصص تفاعلية, برمجة إبداعية, Swift"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].universe %}
{% assign media = site.data.media.universe %}

#### [→ {{ nav.home }}]({{ prefix }}/)

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

#### [→ {{ nav.coding }}]({{ prefix }}/coding/) | [{{ nav.groove }} ←]({{ prefix }}/groove/)