---
layout: default
lang: no
permalink: /no/privacy/
---


{% include locale.liquid %}
{% assign content = site.data.pages[lang].privacy %}

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