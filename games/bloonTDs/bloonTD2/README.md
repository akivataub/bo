---
layout: game
title: Bloons TD 2
folder: games/bloonTDs/bloonTD2
gamefile: bloonstd2.swf
download: true
description: Bloons TD 2 is the second game in the Bloons Tower Defenses series. It is a tower defense game where you must pop the balloons before they reach the end of the track. There are many different types of towers and bloons in this game.
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="500" height="400" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
