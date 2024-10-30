---
layout: game
title: Pokemon Flash Version
folder: games/pokemonflash
gamefile: pokemon_flash_version.swf
download: true
description: "Pokemon Flash Version"
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" wmode="window" width="715" height="525" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
