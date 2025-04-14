---
layout: default
lang: uk
permalink: /uk/creators/
title: "Створено для творців."
description: "Swiftian — це платформа, орієнтована на спільноту, де творці можуть навчатися, ділитися знаннями та створювати нове разом."
keywords: "Swiftian, творці, спільнота програмістів, співпраця"
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