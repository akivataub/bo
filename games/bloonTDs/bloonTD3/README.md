---
layout: game
title: Bloons TD 3
folder: games/bloonTDs/bloonTD3
gamefile: bloonstd3.swf
download: true
description: Bloons TD 3 is the third game in the Bloons Tower Defenses series. It is a tower defense game where you must pop the balloons before they reach the end of the track. There are many different types of towers and bloons in this game.
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="600" height="475" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
