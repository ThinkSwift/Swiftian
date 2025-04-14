---
layout: default
lang: uk
permalink: /uk/universe/
title: "Створи свій власний всесвіт."
description: "Досліджуйте програмування через захопливі історії. Наша науково-фантастична розповідь Mars Rebels робить навчання веселим і інтерактивним."
keywords: "Mars Rebels, сторітелінг, креативне програмування, Swift"
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