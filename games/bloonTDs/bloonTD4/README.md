---
layout: game
title: Bloons TD 4
folder: games/bloonTDs/bloonTD4
gamefile: bloonstd4.swf
download: true
description: Bloons TD 4 is the fourth game in the Bloons Tower Defenses series. It is a tower defense game where you must pop the balloons before they reach the end of the track. There are many different types of towers and bloons in this game.
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="500" height="500" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
