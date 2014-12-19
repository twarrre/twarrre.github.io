---
layout: page
title: Blog
---

## Blog Posts

<div class="blogposts">
  {% for post in site.categories.blog%}
   <div class="blogpost">
    <a href="{{ post.url }}">
      <h3>{{ post.title }}</h3>
      ##<img src="{{ post.image }}" />
    </a>
  </div>
  {% endfor %}
</div>