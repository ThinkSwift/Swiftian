---
layout: default
lang: ar
permalink: /ar/privacy/
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].privacy %}

#### [→ {{ nav.home }}]({{ homePath }})

# {{ content.title }}

{{ content.body | markdownify }}

---

**{{ nav.effective_date }}**