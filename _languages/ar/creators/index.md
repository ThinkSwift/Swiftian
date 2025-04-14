---
layout: default
lang: ar
permalink: /ar/creators/
title: "مصمم للمبدعين."
description: "Swiftian هو مجتمع رقمي يتيح للمبدعين التعلم والمشاركة والابتكار في عالم البرمجة."
keywords: "Swiftian, مبدعين, مجتمع برمجة, تعاون"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [→ {{ nav.groove }}]({{ prefix }}/groove/)

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

#### [→ {{ nav.groove }}]({{ prefix }}/groove/)