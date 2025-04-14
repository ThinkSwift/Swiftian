---
layout: default
lang: ja
permalink: /ja/privacy/
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].privacy %}

#### [← {{ nav.home }}]({{ homePath }})

# {{ content.title }}

{{ content.body | markdownify }}

---

**{{ nav.effective_date }}**