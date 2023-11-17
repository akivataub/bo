---
layout: game
title: "Battalion: Nemesis"
folder: games/battalionnemesis
gamefile: embeddable_22054.swf
download: true
description: "Battalion: Nemesis is a turn-based strategy game where you command an army of soldiers in a series of missions. Each mission will have a different objective, but you will have to use your soldiers strategically in order to complete the mission."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed xmlns="http://www.w3.org/1999/xhtml" height="500" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="700" />
