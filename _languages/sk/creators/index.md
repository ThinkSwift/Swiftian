---
layout: default
lang: sk
permalink: /sk/creators/
title: "Pre tvorcov."
description: "Swiftian je platforma založená na komunite, ktorá podporuje tvorcov pri učení, zdieľaní a spoločných inováciách."
keywords: "Swiftian, tvorcovia, komunita programátorov, spolupráca"
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