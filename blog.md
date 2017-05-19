---
layout: default
permalink: 'blog/'
title: 'Blog'
---

An explanation of the timeline format should go here.

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }} "Read the {{ post.title }} blog post") {{ post.excerpt | remove: '<p>' | remove: '</p>' }}
{% endfor %}
