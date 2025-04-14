---
layout: default
lang: tr
permalink: /tr/coding/
title: "Yarat. Keşfet."
description: "Etkileşimli ve yapılandırılmış derslerle Swift öğrenin. Küçük adımlarla başlayın, büyük düşünün ve becerilerinizi adım adım geliştirin."
keywords: "Swift, Swiftian, Swift öğrenme, programlama kursu, kodlama"
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