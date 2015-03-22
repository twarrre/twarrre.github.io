---
layout: page
title: Blog
tag: Blog
---

<div class="blogposts">
	<div class="blogpost">
		{% for post in site.categories.blog%}
			  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
		{% endfor %}
	</div>
</div>
<br>