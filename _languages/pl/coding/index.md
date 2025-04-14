---
layout: default
lang: pl
permalink: /pl/coding/
title: "Twórz. Odkrywaj."
description: "Ucz się Swift poprzez interaktywne i uporządkowane lekcje. Zaczynaj od podstaw, myśl ambitnie i rozwijaj swoje umiejętności krok po kroku."
keywords: "Swift, Swiftian, nauka Swift, kurs programowania, kodowanie"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].coding %}
{% assign media = site.data.media.coding %}

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

{% include media.html
  type=media.logo.type
  src=media.logo.src
  alt=media.logo.alt
  max=media.logo.max
%}

---

#### [{{ nav.universe }} →]({{ prefix }}/universe/)