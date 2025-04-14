---
layout: default
lang: es
permalink: /es/creators/
title: "Hecho para creadores."
description: "Swiftian es una plataforma orientada a la comunidad donde los creadores pueden aprender, compartir e innovar juntos."
keywords: "Swiftian, creadores, comunidad de programación, colaboración"
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