---
layout: page
title: Journal
img: booksellers.png # Add image post (optional)
permalink: journal
sidebar: true
---

---

{% if site.data.entries %}
## Entries
{% for journal in site.data.entries %}
* [__{{journal.name}}__]({{site.url}}/{{site.baseurl}}/{{journal.location}})
  \| {{journal.desc}}
{% endfor %}
{% endif %}
