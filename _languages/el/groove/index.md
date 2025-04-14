---
layout: default
lang: el
permalink: /el/groove/
title: "Κινηθείτε με τον ρυθμό."
description: "Επιλεγμένη μουσική που ενισχύει την παραγωγικότητα και τη δημιουργικότητα κατά την κωδικοποίηση. Εστιάστε καλύτερα με ρυθμό."
keywords: "μουσική για προγραμματισμό, παραγωγικότητα, δημιουργικότητα, μουσική, Swiftian"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].groove %}
{% assign media = site.data.media.groove %}

#### [← {{ nav.universe }}]({{ prefix }}/universe/)

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