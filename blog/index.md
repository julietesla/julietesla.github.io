---
layout: default
title: Blog
---

# {{ page.title }}

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{% endfor %}
