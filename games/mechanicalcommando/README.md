---
layout: game
title: Mechanical Commando
folder: games/mechanicalcommando
gamefile: embeddable_31946.swf
download: true
description: "Mechanical Commando is a game where you play as a robot and shoot other robots."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed xmlns="http://www.w3.org/1999/xhtml" height="550" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="700" />
