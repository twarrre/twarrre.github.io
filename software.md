---
layout: page
title: Software
---

<div class="softwares">
	<table border="0">
		{% for post in site.categories.software%}
			<tr>
				<td>
					<a href="{{ post.url }}">
						<img src="{{ post.image }}" height="200" width="400px" border="1px"/>
					</a>
				</td>
				<td>
					<a href="{{ post.url }}">
						<h3>{{ post.title }}</h3>
					</a>
				</td>
			</tr>
		{% endfor %}
	</table>
</div>