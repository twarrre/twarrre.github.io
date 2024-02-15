---
layout: game
title: "Hardspace: Shipbreaker"
image: /assets/shipbreaker/shipbreaker_banner_small.jpg
desc: "Cut up spaceships to recover valuable materials and pay your debt to LYNX Corp!"
tag: Games
gallery: shipbreakerGallery
---

Hardspace: Shipbreaker was the first game that I worked on professionally in the video game industry for Blackbird Interactive. I started on the project in 2016, shortly after the original team had completed a game jam to come up with the concept of Shipbreaker. Over the next few years the game went through several iterations until we found the blue-collar fantasy tone and shipbreaking gameplay.

The game was released in early access in 2020 and was published by Focus Entertainment. We continued to work on it for two more years and released the complete game on PC in 2022, with console ports released shortly after.

<div class="video">
	<iframe src="https://www.youtube.com/embed/4NkAkbwiO8g?si=QyjrN909R2MVDUcH" frameborder="0" allowfullscreen="1"></iframe>
</div>

I was a generalist programmer on the project. I implemented and supported many different features for the game. Later in the project I also took on some leadership responsibilities and people management roles.

My favourite feature to implement was the grappling hook. Using a custom spring and damper system, we were able to make a tool that could be used for both player traversal and object manipulation. We focused on traversal first, with the goal of making the player feel like Spider-Man in space. Later, we implemented ways that the grapple could move objects depending on the mass ratio between the player and the object.

I also worked on the elemental system of Shipbreaker. It was inspired by Breath of the Wild’s chemistry system. We took advantage of Unity’s ECS and Jobs systems to be able to implement this system. We added components to objects with specific properties like “Flammable”, “Freezable” or “Explosive”. We would use component systems to query entities with these tags and process the reaction accordingly. I also implemented some complex audio systems in relation to the elemental system so that we would not overload our audio engine.

Below is a Unite talk that I participated in explaining how we implemented the explosion visual effects in Hardspace: Shipbreaker. 

<div class="video">
	<iframe src="https://www.youtube.com/embed/VWjn3MQHWC8?si=alHGXUt81Lj4Eu-7" frameborder="0" allowfullscreen="1"></iframe>
</div>

Hardspace: Shipbreaker is avaiable on <a href="https://store.steampowered.com/app/1161580/Hardspace_Shipbreaker/">Steam</a>, <a href="https://store.epicgames.com/en-US/p/hardspace-shipbreaker">Epic</a>, <a href="https://www.gog.com/en/game/hardspace_shipbreaker">GOG</a>, <a href="https://www.xbox.com/en-US/games/store/hardspace-shipbreaker/9ND8C4314ZZG">Xbox</a> and <a href="https://store.playstation.com/en-us/product/UP4133-PPSA07301_00-HARDSPACESHIPBRK">Playstation</a>.

### Developed With:
* __Platform:__ PC, Xbox Series, PS5
* __Engine:__ Unity
* __Programming Language:__ C#