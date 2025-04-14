---
layout: default
lang: el
permalink: /el/coding/
title: "Δημιουργήστε. Εξερευνήστε."
description: "Μάθετε Swift με διαδραστικά και δομημένα μαθήματα. Ξεκινήστε απλά, σκεφτείτε μεγάλα και αναπτύξτε τις δεξιότητές σας σταδιακά."
keywords: "Swift, Swiftian, εκμάθηση Swift, μαθήματα προγραμματισμού, κώδικας"
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