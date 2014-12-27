---
layout: page
title: Blog
tag: Blog
---

<div class="blogposts">
	<div class="blogpost">
		{% for post in site.categories.blog%}
			* [{{ post.title }}  -  {{ post.date | date_to_string }}]({{ post.url }})
		{% endfor %}
	</div>
</div>
<br>