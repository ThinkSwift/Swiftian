---
layout: default
lang: fr
permalink: /fr/
title: "Think Swift."
description: "Commencez votre parcours créatif en programmation avec Swiftian — une plateforme interactive et soigneusement conçue pour apprendre Swift."
keywords: "Swiftian, Swift, apprendre à coder, développement mobile, apprendre Swift"
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