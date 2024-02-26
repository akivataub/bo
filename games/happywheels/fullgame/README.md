---
layout: game
title: Happy Wheels Full Game
folder: games/happywheels/fullgame
gamefile: HappyWheelsFull.zip
download: false
description: "Happy Wheels is a ragdoll-physics adventure game. The goal is to get to the finish line without getting killed."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<a href="{{ cdn_url }}" download class="btn btn-outline-dark">Download Full Game</a>
