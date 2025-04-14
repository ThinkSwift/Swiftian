---
layout: default
lang: id
permalink: /id/
title: "Think Swift."
description: "Mulai perjalanan kreatif Anda dalam dunia pemrograman bersama Swiftian — platform interaktif yang dirancang untuk belajar Swift secara efektif."
keywords: "Swiftian, Swift, belajar coding, pengembangan mobile, belajar Swift"
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