---
layout: page
title: Games
---

<div class="games">
  {% for post in site.categories.games%}
   <div class="game">
    <a href="{{ post.url }}">
      <h3>{{ post.title }}</h3>
    </a>
  </div>
  {% endfor %}
</div>