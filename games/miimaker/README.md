---
layout: game
title: Mii Maker
folder: games/miimaker
gamefile: miimakerflash.swf
download: true
description: "Mii Maker is a game where you create your own Mii character."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<!-- <embed src="{{ cnd_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="500" height="450" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer"> -->

<embed xmlns="http://www.w3.org/1999/xhtml" height="550" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="700" />
