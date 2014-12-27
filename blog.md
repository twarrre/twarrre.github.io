---
layout: page
title: Blog
tag: Blog
---

<div class="blogposts">
	<div class="blogpost">
		<ul>
			{% for post in site.categories.blog%}
				<li>
					<a id="menu" href="{{ post.url }}">
					  {{ post.title }}  -  {{ post.date | date_to_string }}
					</a>
				</li>
			{% endfor %}
		</ul>
	</div>
</div>
<br>