---
layout: page
title: Blog
tag: Blog
---

<div class="blogposts">
<table>
{% for post in site.categories.blog%}
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
				{{ post.date | date: "%-d %B %Y" }}
			</p>
			</div>
		</td>
	</tr>
{% endfor %}
</table>
</div>
