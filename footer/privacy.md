---
layout: default
lang: en
permalink: /privacy/
title: "Privacy Policy"
robots: noindex, nofollow
description: "Swiftian Privacy Policy page."
---

{% include locale.liquid %}
{% assign content = site.data.pages[lang].privacy %}

#### [← {{ nav.home }}]({{ homePath }})

# {{ content.title }}

{{ content.body | markdownify }}

---

**{{ nav.effective_date }}**
