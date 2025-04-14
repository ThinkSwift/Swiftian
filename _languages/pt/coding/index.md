---
layout: default
lang: pt
permalink: /pt/coding/
title: "Crie. Explore."
description: "Aprenda Swift com lições estruturadas e interativas. Comece com o básico, pense grande e desenvolva suas habilidades passo a passo."
keywords: "Swift, Swiftian, aprender Swift, curso de programação, codificação"
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