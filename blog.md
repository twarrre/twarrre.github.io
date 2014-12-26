---
layout: page
title: Blog
tag: Blog
---

<div class="blogposts">
	<div class="blogpost">
		<ul>
			{% for post in site.categories.blog%}
				<a href="{{ post.url }}">
				  <li>{{ post.title }}</li>
				</a>
			{% endfor %}
		</ul>
	</div>
</div>