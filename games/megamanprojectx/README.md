---
layout: game
title: Megaman Project X
folder: games/megamanprojectx
gamefile: megaman-project-x-flash.swf
download: true
description: "Megaman Project X is a game where you play as Megaman and shoot other robots."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="800" height="500" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
