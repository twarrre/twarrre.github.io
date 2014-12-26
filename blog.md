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
					<a href="{{ post.url }}">
					  {{ post.title }}
					</a>
				</li>
			{% endfor %}
		</ul>
	</div>
</div>
<br>
<br>