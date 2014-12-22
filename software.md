---
layout: page
title: Software
tag: Software
---

<div class="softwares">
	<table>
		{% for post in site.categories.software%}
			<tr>
				<a href="{{ post.url }}">
					<td style="Width: 200px">					
						<img src="{{ post.image }}" height="200px" width="200px" border="1px"/>
					</td>
					<td>
						<h3>{{ post.title }}</h3>
						<p>
							{{ post.desc }}
						</p>
					</td>
				</a>
			</tr>
		{% endfor %}
	</table>
</div>