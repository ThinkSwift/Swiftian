---
layout: default
lang: en
permalink: /coding/
title: "Create. Explore."
description: "Learn Swift through curated, interactive lessons. Start small, think big, and master coding step by step."
keywords: "Swiftian, Swift, coding, learn Swift, mobile development"
---

{% include locale.liquid %}
{% assign content = site.data.pages[lang].coding %}
{% assign media = site.data.media.coding %}

#### [{{ arrow_left }} {{ nav.home }}]({{ prefix }}/)

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

#### [{{ nav.universe }} {{ arrow_right }}]({{ prefix }}/universe/)
