---
layout: default
lang: el
permalink: /el/
title: "Think Swift."
description: "Ξεκινήστε το δημιουργικό σας ταξίδι στον προγραμματισμό με το Swiftian – μια διαδραστική και επιλεγμένη πλατφόρμα για να μάθετε Swift αποτελεσματικά."
keywords: "Swiftian, Swift, μάθε προγραμματισμό, ανάπτυξη εφαρμογών, εκμάθηση Swift"
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