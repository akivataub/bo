---
layout: game
title: Papa's Cupcakeria
folder: games/paparestaurants/cupcakeria
gamefile: papascupcakeria-Events.swf
download: true
# description: 
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<object xmlns="http://www.w3.org/1999/xhtml" data="{{ cdn_url }}" height="480" id="swfObjID" type="application/x-shockwave-flash" width="640">
    <param name="allowScriptAccess" value="always">
    <param name="movie" value="{{ cdn_url }}">
    <param name="menu" value="false">
    <param name="quality" value="high">
    <param name="wmode" value="direct">
</object>

<p><br> Instructions
    <br> To start the game just click on the"save slot" cards. I had the name entry disabled so no one can get creative with the names! ;-)
    <br> Take the customer's order... Make the cupcakes... Give it to the customer. If it's done correctly, you get a big tip!
    <br> It gets hard when there is more than one customer to deal with at once!
    <br>
</p>