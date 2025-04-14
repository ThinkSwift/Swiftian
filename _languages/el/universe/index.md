---
layout: default
lang: el
permalink: /el/universe/
title: "Χτίστε το δικό σας σύμπαν."
description: "Ανακαλύψτε τον προγραμματισμό μέσω καθηλωτικής αφήγησης. Η sci-fi ιστορία Mars Rebels κάνει την εκμάθηση διασκεδαστική και διαδραστική."
keywords: "Mars Rebels, αφήγηση, δημιουργικός προγραμματισμός, Swift"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].universe %}
{% assign media = site.data.media.universe %}

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

---

#### [← {{ nav.coding }}]({{ prefix }}/coding/) | [{{ nav.groove }} →]({{ prefix }}/groove/)