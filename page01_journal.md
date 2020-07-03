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
* [:star2:{{journal.name}}:star2:]({{site.url}}/{{site.baseurl}}/{{journal.location}})
  \| {{journal.desc}}
{% endfor %}
{% endif %}
