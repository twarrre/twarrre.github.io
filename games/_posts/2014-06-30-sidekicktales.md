---
layout: game
title: "Sidekick Tales: Limbitless"
image: /assets/sidekick/sidekick_banner_small.png
desc: "An adventure game, where you must borrow the local animal's powers in order to rescue Supman."
tag: Games
gallery: sidekickGallery
---
##{{ page.title }}

You live in a village with fellow chicken herders and every year you and your fellow villagers celebrate the ten days of Cluckmas to appease the chicken god Cluck. On each of the ten days of Cluckmas, you offer a certain amount of chickens to Cluck, however if you do not have the right number of chickens, Cluck will smite your village and turn all of you into goats. Unfortunately, one unruly chicken herder keeps releasing all of the chickens so close to Cluck's arrival. Now it is up to you to catch all of the chickens before Cluck arrives and turns you into a goat! To catch the chickens you must crouch, sprint and slide, but you must be sneaky because the chickens will run away if you get too close.  Once you catch the chicken, you will have to quickly toss them into the pen, because if you hold on to them too long you might drop them. 

<div class="video">
	<iframe src="//www.youtube.com/embed/aiNcoj9zleA" frameborder="0" allowfullscreen="1"></iframe>
</div>
	
This game was developed by a team of four during my first term of video game development at BCIT. My role included programming the player and camera movement including sprinting, crouching, sliding, and catching, toon and skinned animation shaders, programming the audio sound effects, as well as programming the HUD for the game.

###Developed With:
* Framework: Unity
* Programming Language: C#
* IDE: MonoDevelop / Visual Studio 2013

###Images

<ul class="rig columns-2">
	{% for gallery in site.data.galleries %}
		{% if page.gallery == gallery.id %}
			{% for image in gallery.images %}
				<li>
					<img src="{{ gallery.imagefolder }}/{{ image.name }}" />
				</li>
			{% endfor %}
		{% endif %}
	{% endfor %}
</ul>