---
layout: page
title: Software
tag: Software
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
						<p>
							{{ post.desc }}
						</p>
					</a>
				</td>
			</tr>
		{% endfor %}
	</table>
</div>