---
layout: game
title: Demons Took My Daughter
folder: games/demonstookmydaughter
gamefile: embeddable_96829.swf
download: true
description: "Rescue your daughter from the evil (and adorable!) Demons in this hybrid platformer/defence game! Fight a wide variety of enemies (and the 7 Deadly Sins) on your epic quest!"
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed xmlns="http://www.w3.org/1999/xhtml" height="500" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="550" />
