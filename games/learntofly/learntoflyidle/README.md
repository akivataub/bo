---
layout: game
title: Learn To Fly Idle
folder: games/learntofly/learntoflyidle
gamefile: embeddable_203284.swf
download: true
description: "Learn to Fly Idle is a game where you play as a penguin trying to prove to the world that penguins can fly."
---


{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed xmlns="http://www.w3.org/1999/xhtml" height="540" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="720" />
