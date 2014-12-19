---
layout: page
title: Software
---

<div class="softwares">
  {% for post in site.categories.software%}
   <div class="software">
    <a href="{{ post.url }}">
      <h3>{{ post.title }}</h3>
    </a>
  </div>
  {% endfor %}
</div>