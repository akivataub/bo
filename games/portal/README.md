---
layout: game
title: "Portal: The Flash Verison"
folder: games/portal
gamefile: Portal.swf
download: true
description: "Portal: The Flash Verison"
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" wmode="window" width="800" height="500" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
