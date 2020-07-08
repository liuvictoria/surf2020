---
layout: page
title: Journal
img: journaling.png # Add image post (optional)
caption: "Life Teen"
permalink: journal
sidebar: true
---

---

{% if site.data.entries %}
## Entries

**These journal entries serve more as summaries and important notes for my personal reference when I write my SURF reports; they aren't meant to be comprehensive summaries of the works. For example, if I'm really familiar with certain tropes / laws already, I probably won't mention them in the summary.**

{% for journal in site.data.entries %}
* [:star2:{{journal.name}}:star2:]({{site.url}}/{{site.baseurl}}/{{journal.location}})
  \| {{journal.desc}}
{% endfor %}
{% endif %}
