---
layout: game
title: Alien Hominid
folder: games/alienhominid
gamefile: alien_hominid.swf
description: Alien Hominid is a side-scrolling shooter that has you playing as an alien that has crash landed on Earth and must fight off the FBI and other enemies to get back to his home planet.
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" wmode="window" width="500" height="400" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
