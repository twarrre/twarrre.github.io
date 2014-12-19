---
layout: page
title: Blog
---

<div class="blogposts">
  {% for post in site.categories.blog%}
   <div class="blogpost">
    <a href="{{ post.url }}">
      <h3>{{ post.title }}</h3>
    </a>
  </div>
  {% endfor %}
</div>