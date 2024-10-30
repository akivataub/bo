---
layout: game
title: Mr Runner
folder: games/mrrunner
gamefile: embeddable_76395.swf
download: true
description: "Mr Runner is a game where you play as a character and run through levels."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed xmlns="http://www.w3.org/1999/xhtml" height="480" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="800">
