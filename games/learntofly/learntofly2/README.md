---
layout: game
title: Learn To Fly 2
folder: games/learntofly/learntofly2
gamefile: embeddable_115608.swf
download: true
description: "Learn to Fly 2 is a game where you play as a penguin trying to prove to the world that penguins can fly."
---


{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed xmlns="http://www.w3.org/1999/xhtml" base="" height="480" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="640" />
