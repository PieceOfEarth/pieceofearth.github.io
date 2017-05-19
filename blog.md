---
layout: default
permalink: 'blog/'
title: 'Blog'
---

We have tried to keep a blog as a record of our activities and as a learning resource for other groups wishing to undertake a similar journey. Blog entries are accompanied by _perspectives_, written by individual community members, and photographs where possible.

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }} "Read the {{ post.title }} blog post") {{ post.excerpt | remove: '<p>' | remove: '</p>' }}
{% endfor %}
