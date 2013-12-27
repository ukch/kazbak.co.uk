---
layout: default
title: Blog archive
section: blog
---

# {{ page.title }}

{% for post in site.posts do %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}
