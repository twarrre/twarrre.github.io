---
layout: page
title: Art
---

## Art Posts

<div class="arts">
  {% for post in site.categories.art%}
   <div class="art">
    <a href="{{ post.url }}">
      <h3>{{ post.title }}</h3>
      ##<img src="{{ post.image }}" />
    </a>
  </div>
  {% endfor %}
</div>