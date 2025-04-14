---
layout: default
lang: pl
permalink: /pl/
title: "Think Swift."
description: "Rozpocznij swoją kreatywną podróż programistyczną ze Swiftian — interaktywną i starannie opracowaną platformą do nauki języka Swift."
keywords: "Swiftian, Swift, nauka programowania, rozwój mobilny, nauka Swift"
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