---
layout: default
permalink: 'blog/'
title: 'Blog'
---

We have tried to keep a blog as a record of our activities and as a learning resource for other groups wishing to undertake a similar journey. Blog entries are accompanied by _perspectives_, written by individual community members, and photographs where possible.

{% for post in site.posts %}
  <div class="post-timeline-container">
    <div class="post-timeline-left">
      <div class="post-date">
        {{ post.date | date: "%-d %B %Y" }}
      </div>
    </div>
    <div class="post-timeline-right">
      <div class="post-title">
        <a href="{{ post.url }}" title="Read the {{ post.title }} blog post">{{ post.title }}</a>
      </div>
      <div class="post-excerpt">
        {{ post.excerpt }}
      </div>
    </div>
  </div>
{% endfor %}
