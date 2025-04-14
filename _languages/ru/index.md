---
layout: default
lang: ru
permalink: /ru/
title: "Think Swift."
description: "Начни свое креативное путешествие в программировании с Swiftian — интерактивной платформой, разработанной для эффективного изучения Swift."
keywords: "Swiftian, Swift, изучение программирования, мобильная разработка, изучить Swift"
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