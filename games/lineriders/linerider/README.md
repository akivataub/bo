---
layout: game
title: Line Rider
folder: games/lineriders/linerider
gamefile: line_rider.swf
download: true
description: "Line Riders is a game where you draw a line and a little guy on a sled rides it."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="800" height="600" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
