---
layout: page
title: Software
---

<div class="softwares">
	{% for post in site.categories.software%}
		<div class="software">
			<p style="float: left;">
				<a href="{{ post.url }}">
					<img src="{{ post.image }}" height="200" width="400px" border="1px"/>
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