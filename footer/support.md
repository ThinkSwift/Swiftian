---
layout: default
lang: en
permalink: /support/
title: "Support"
robots: noindex, nofollow
description: "Swiftian Support page."
---

{% include locale.liquid %}
{% assign content = site.data.pages[lang].support %}

#### [← {{ nav.home }}]({{ prefix }}/)

# {{ content.title }}

{% for section in content.sections %}
### {{ section.heading }}

{% if section.text %}
{{ section.text | markdownify }}
{% endif %}

{% if section.bullets %}
<ul>
  {% for bullet in section.bullets %}
    <li>{{ bullet }}</li>
  {% endfor %}
</ul>
{% endif %}

{% endfor %}


---

**Effective Date: {{ content.effective_date }}**
