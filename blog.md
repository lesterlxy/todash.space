---
layout: default
title: blog
permalink: /blog/
---

# blog

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

[&larr; Home]({{ "/" | relative_url }})
