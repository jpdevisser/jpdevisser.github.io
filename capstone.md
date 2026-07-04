---
layout: page
title: Capstone Project
permalink: /capstone/
---

{% for post in site.categories.capstone %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}