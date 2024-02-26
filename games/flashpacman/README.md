---
layout: game
title: Flash Pacman
folder: games/flashpacman
gamefile: pacman-flash.swf
download: true
description: "Flash Pacman is a classic arcade game that was first released in 1980. The game was created by Namco and it quickly became a popular game in arcades around the world. In this game, you play as Pacman, a yellow circle with a mouth, and your goal is to eat all of the dots in the maze while avoiding the ghosts. The game features four different types of ghosts, each with their own unique behavior. The game has a retro pixel art style and the gameplay is fast-paced and challenging. If you are a fan of classic arcade games, you will enjoy playing Flash Pacman."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" wmode="window" width="520" height="600" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
<br>
<br>
<p>
Use the arrow keys to move Pacman, eat the dots avoid the ghosts. Add your high score to our Pacman high score list.
</p>
