---
layout: game
title: Happy Wheels Demo
folder: games/happywheels/demo
gamefile: HappyWheels.swf
download: true
description: "Happy Wheels is a ragdoll-physics adventure game. The goal is to get to the finish line without getting killed."
---


{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<object type="application/x-shockwave-flash" data="{{ cdn_url }}" id="swfObjID" width="800px" height="600px"></object>
