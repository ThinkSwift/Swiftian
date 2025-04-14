---
layout: default
lang: fi
permalink: /fi/creators/
title: "Luoville tekijöille."
description: "Swiftian on yhteisölähtöinen alusta, jossa luovat tekijät voivat oppia, jakaa ja innovoida yhdessä."
keywords: "Swiftian, luovat tekijät, koodausyhteisö, yhteistyö"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].creators %}
{% assign media = site.data.media.creators %}

#### [← {{ nav.groove }}]({{ prefix }}/groove/)

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

#### [← {{ nav.groove }}]({{ prefix }}/groove/)