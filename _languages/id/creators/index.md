---
layout: default
lang: id
permalink: /id/creators/
title: "Dibuat untuk para kreator."
description: "Swiftian adalah platform berbasis komunitas bagi para kreator untuk belajar, berbagi, dan berinovasi bersama."
keywords: "Swiftian, kreator, komunitas coding, kolaborasi"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [← {{ nav.home }}]({{ prefix }}/)

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