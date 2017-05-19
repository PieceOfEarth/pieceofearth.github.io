---
layout: default
permalink: 'gallery/'
title: 'Gallery'
---

Here are a selection of photographs from the project.

{% assign image_files = site.static_files | where: "image", true %}

{% for img in image_files %}
  <div class="img-thumb">
    <a href="{{ img.path }}">
      <img src="{{ img.path }}" />
    </a>
  </div>
{% endfor %}
