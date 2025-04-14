---
layout: default
lang: ar
permalink: /ar/coding/
title: "أنشئ. استكشف."
description: "تعلم Swift من خلال دروس تفاعلية ومنظمة. ابدأ بخطوات بسيطة وارتقِ بمهاراتك في البرمجة خطوة بخطوة."
keywords: "Swift, Swiftian, تعلم Swift, دروس برمجة, تطوير تطبيقات"
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].coding %}
{% assign media = site.data.media.coding %}

#### [→ {{ nav.home }}]({{ prefix }}/)

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

#### [{{ nav.universe }} ←]({{ prefix }}/universe/)