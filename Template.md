---
layout: game
title: TITLE
folder: games/TITLE
gamefile: TITLE.swf
download: true
description: DESCRIPTION
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<!-- Whatever needs to go here -->