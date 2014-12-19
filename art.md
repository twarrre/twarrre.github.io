---
layout: page
title: Art
---

<div class="arts">
	{% for post in site.categories.art%}
		<div class="art">
			<a href="{{ post.url }}">
				<img src="{{ post.image }}" />
				<h3>{{ post.title }}</h3>
			</a>
		</div>
	{% endfor %}
</div>