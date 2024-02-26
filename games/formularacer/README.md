---
layout: game
title: Formula Racer
folder: games/formularacer
gamefile: embeddable_109268.swf
download: true
# description: 
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed xmlns="http://www.w3.org/1999/xhtml" height="480" src="{{ cdn_url }}" type="application/x-shockwave-flash" width="640" />
