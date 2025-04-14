---
layout: default
lang: pl
permalink: /pl/groove/
title: "Ruszaj się w rytmie."
description: "Specjalnie wybrana muzyka wspomagająca koncentrację i kreatywność podczas kodowania. Popraw swój rytm pracy dzięki dźwiękom."
keywords: "muzyka do programowania, produktywność, kreatywność, skupienie, Swiftian"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].groove %}
{% assign media = site.data.media.groove %}

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
  type=media.preview.type
  src=media.preview.src
  max=media.preview.max
  controls=media.preview.controls
%}

---

#### [← {{ nav.universe }}]({{ prefix }}/universe/) | [{{ nav.creators }} →]({{ prefix }}/creators/)