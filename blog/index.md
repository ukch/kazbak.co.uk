---
layout: default
title: Blog archive
section: blog
---

# {{ page.title }}

{% for post in site.posts do %}
* [{{ post.title }}]({{ post.url }}) ({{ post.date  | date: "%-d %B %Y"}})
{% endfor %}

[Older articles](http://blog.kazbak.co.uk/blog/)
