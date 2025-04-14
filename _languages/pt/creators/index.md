---
layout: default
lang: pt
permalink: /pt/creators/
title: "Feito para criadores."
description: "Swiftian é uma plataforma voltada para a comunidade onde criadores podem aprender, compartilhar e inovar juntos."
keywords: "Swiftian, criadores, comunidade de programação, colaboração"
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