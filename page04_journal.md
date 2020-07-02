---
layout: page
title: Journal
img: booksellers.png # Add image post (optional)
permalink: journal
sidebar: true
---

---

{% if site.data.entries %}
## Entries (from latest to oldest)
{% for journal in site.data.entries %}
* [**{{journal.name}}**]({{site.url}}/{{site.baseurl}}/{{journal.location}})
  \| {{journal.desc}}
{% endfor %}
{% endif %}
