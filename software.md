---
layout: page
title: Software
---

<div class="softwares">
	{% for post in site.categories.software%}
		<div class="software">
			<p style="float: left;">
				<a href="{{ post.url }}">
					<img src="{{ post.image }}" height="400" width="200px" border="20px"/>
				</a>
			</p>
			<p>
				<a href="{{ post.url }}">
					<h3>{{ post.title }}</h3>
				</a>
			</p>
	</div>
	{% endfor %}
</div>