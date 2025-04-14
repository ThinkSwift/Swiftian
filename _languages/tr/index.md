---
layout: default
lang: tr
permalink: /tr/
title: "Think Swift."
description: "Swiftian ile yaratıcı programlama yolculuğuna başlayın — Swift öğrenmek için etkileşimli ve özenle hazırlanmış bir platform."
keywords: "Swiftian, Swift, programlama öğrenme, mobil geliştirme, Swift öğren"
---

{% include locale.liquid %}
{% assign content = site.data.pages[lang].home %}

# {{ content.title }}

{% include video.html src="/assets/videos/logo.mp4" id="logoVideo" soundIconId="soundIcon" %}

{{ content.text | newline_to_br }}

- [{{ nav.coding }} →]({{ prefix }}/coding/)
- [{{ nav.universe }} →]({{ prefix }}/universe/)
- [{{ nav.groove }} →]({{ prefix }}/groove/)
- [{{ nav.creators }} →]({{ prefix }}/creators/)

---
{% include footer.html %}