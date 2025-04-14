---
layout: default
lang: fi
permalink: /fi/groove/
title: "Liiku rytmissä."
description: "Huolella valittu musiikki tukee keskittymistä ja luovuutta ohjelmoinnin aikana. Saavuta virtausrytmi musiikin avulla."
keywords: "koodausmusiikki, tuottavuus, keskittyminen, luovuus, Swiftian"
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