---
layout: game
title: Donkey Kong Flash
folder: games/donkeykong
gamefile: donkey-kong-returns.swf
download: true
description: "Donkey Kong is back! Play the remake of the old-school NES classic."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" wmode="window" width="600" height="500" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
