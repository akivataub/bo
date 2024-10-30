---
layout: game
title: Candy Crush
folder: games/candycrush
gamefile: candy-crush.swf
download: true
description: Candy Crush is a match 3 game where you must match 3 or more candies to remove them from the board. You can also match 4 or 5 candies to get special candies that can be used to remove more candies from the board.
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="755" height="600" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
