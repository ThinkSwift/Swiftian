---
layout: default
lang: en
permalink: /coding/
title: "Create. Explore."
description: "Learn Swift through curated, interactive lessons. Start small, think big, and master coding step by step."
keywords: "Swiftian, Swift, coding, learn Swift, mobile development"
---
{% include locale.liquid %}
{% assign content = site.data.pages.coding[lang] %}

# {{ content.title }}

<p align="center">
  <img src="/assets/images/coding_panic.gif" alt="Coding Panic" style="width: 100%; max-width: 250px; height: auto;">
</p>

{% for section in content.sections %}
### {{ section.heading }}
{{ section.text }}
{% endfor %}

<p align="center">
  <img src="/assets/images/swiftian_logo_180.png" alt="Swiftian: Learn to Code" style="width: 100%; max-width: 80px; height: auto;">
</p>

---

#### [Build Your Universe →](/universe/)
