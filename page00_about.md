---
layout: page
title: About
description: Information about the project, website, and links to the paper and SI
img: booksellers.png # Add image post (optional)
caption: "The Booksellers (2019)"
permalink: index.html
sidebar: true
---

---


# {{site.data.about.title}}
:cherry_blossom:{{site.data.about.authors}}:cherry_blossom:

{% for entry in site.data.about %}

{% if entry[0] != 'title' %}
{% if entry[0] != 'authors' %}
## {{entry[0]}}
{{entry[1]}}
{% endif %}
{% endif %}
{% endfor %}
