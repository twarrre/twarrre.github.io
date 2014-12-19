---
layout: page
title: Games
---

<div class="games">
		<table>
		{% for post in site.categories.games%}
			<tr>
				<td style="width:400px">
					<a href="{{ post.url }}">
						<img src="{{ post.image }}" height="200px" width="400px" border="1px"/>
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