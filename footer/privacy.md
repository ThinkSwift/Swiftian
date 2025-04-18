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

#### [← {{ nav.home }}]({{ prefix }}/)

# {{ content.title }}

{% for section in content.sections %}
### {{ section.heading }}
{{ section.text | markdownify }}
{% endfor %}

---

**Effective Date: {{ content.effective_date }}**
