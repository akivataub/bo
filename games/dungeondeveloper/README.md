---
layout: game
title: Dungeon Developer
folder: games/dungeondeveloper
gamefile: embeddable_98243.swf
download: true
description: "Donkey Kong is back! Play the remake of the old-school NES classic."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed xmlns="http://www.w3.org/1999/xhtml" height="650" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="550" />
