---
layout: default
lang: id
permalink: /id/coding/
title: "Ciptakan. Jelajahi."
description: "Belajar Swift lewat pelajaran interaktif dan terstruktur. Mulai dari dasar, berpikir besar, dan tingkatkan kemampuan Anda langkah demi langkah."
keywords: "Swift, Swiftian, belajar Swift, kursus pemrograman, coding"
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