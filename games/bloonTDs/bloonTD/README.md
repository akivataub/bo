---
layout: game
title: Bloons TD
folder: games/bloonTDs/bloonTD
gamefile: bloonstd_moved.swf
download: true
description: Bloons TD is the first game in the Bloons Tower Defense series. It is a tower defense game where you must pop the balloons (called bloons in the game) before they reach the end of the track. You can pop the bloons by placing towers that shoot darts, tacks, bombs, and ice. Each tower has its own strengths and weaknesses, so you must place them strategically to pop the bloons.
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="600" height="500" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
