---
layout: default
lang: el
permalink: /el/creators/
title: "Για δημιουργούς."
description: "Το Swiftian είναι μια κοινότητα για δημιουργούς που θέλουν να μάθουν, να μοιραστούν και να καινοτομήσουν μαζί."
keywords: "Swiftian, δημιουργοί, κοινότητα προγραμματισμού, συνεργασία"
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