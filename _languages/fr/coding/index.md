---
layout: default
lang: fr
permalink: /fr/coding/
title: "Créer. Explorer."
description: "Apprenez Swift grâce à des leçons interactives et structurées. Commencez petit, pensez grand et progressez étape par étape."
keywords: "Swift, Swiftian, apprendre Swift, cours de programmation, codage"
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