---
layout: page
title: Games
tag: Games
---

<div class="games">
	<table>
		{% for post in site.categories.games%}
			<tr>
				<td style="Width: 200px">
					<a href="{{ post.url }}">
						<img src="{{ post.image }}" height="192px" width="192px" border="1px"/>
					</a>
				</td>
				<td>
				<div class="tableitem">
					<a class="list" href="{{ post.url }}">
						<h3>{{ post.title }}</h3>
					</a>
					<p>
						{{ post.desc }}
					</p>
					<p>
						{{ post.date | date: "%b %Y" }}
					</p>
					</div>
				</td>
			</tr>
		{% endfor %}
	</table>
</div>
