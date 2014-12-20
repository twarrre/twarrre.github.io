---
layout: page
title: Software
---

<div class="softwares">
	<table>
		{% for post in site.categories.software%}
			<tr>
				<td style="Width: 200px">
					<a href="{{ post.url }}">
						<img src="{{ post.image }}" height="200px" width="200px" border="1px"/>
					</a>
				</td>
				<td>
					<a href="{{ post.url }}">
						<h3>{{ post.title }}</h3>
					</a>
					<p>
						{{ post.desc }}
					</p>
				</td>
			</tr>
		{% endfor %}
	</table>
</div>