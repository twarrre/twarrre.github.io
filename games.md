---
layout: page
title: Games
---

## Game Posts

<div class="games">
  {% for post in site.categories.games%}
   <div class="game">
    <a href="{{ post.url }}">
      <h3>{{ post.title }}</h3>
      ##<img src="{{ post.image }}" />
    </a>
  </div>
  {% endfor %}
</div>