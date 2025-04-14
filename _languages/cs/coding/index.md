---
layout: default
lang: cs
permalink: /cs/coding/
title: "Tvoř. Objevuj."
description: "Naučte se Swift pomocí interaktivních a strukturovaných lekcí. Začněte jednoduše, rozvíjejte své dovednosti krok za krokem."
keywords: "Swift, Swiftian, naučte se Swift, kurzy programování, vývoj aplikací"
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