---
layout: game
title: Papa's Pizzaeria
folder: games/paparestaurants/pizzaeria
gamefile_1: papaspizzeria.swf
gamefile_2: papaspizzeria_coolmath_update.swf
download: false
# description: 
---

{% assign cdn_url_1 = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile_1 %}

{% assign cdn_url_2 = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile_2 %}

<!--<object xmlns="http://www.w3.org/1999/xhtml" data="//www.coolmath-games.com/sites/cmatgame/files/games/papaspizzeria_coolmath_update.swf" height="480" id="swfObjID" type="application/x-shockwave-flash" width="640"><param name="allowScriptAccess" value="always"><param name="movie" value="papaspizzeria_coolmath_update.swf"><param name="menu" value="false"><param name="quality" value="high"><param name="wmode" value="direct"></object>-->

<!--<iframe width="640" height="480" scrolling="no" frameborder="0" id="522042934" name="522042934" allowtransparency="true" class="igm" src="https://jujo00obo2o234ungd3t8qjfcjrs3o6k-a-sites-opensocial.googleusercontent.com/gadgets/ifr?url=http://www.gstatic.com/sites-gadgets/embed/embed.xml&container=enterprise&view=home&lang=en&country=ALL&sanitize=0&v=9caee3fe549fd13b&libs=core:setprefs&parent=https://sites.google.com/site/boredschoolrightnow/games/papa-s-restaurants/papa-s-pizzeria#up_embed_snippet=%3Cobject+xmlns%3D%22http://www.w3.org/1999/xhtml%22+data%3D%22//www.coolmath-games.com/sites/cmatgame/files/games/papaspizzeria_coolmath_update.swf%22+height%3D%22480%22+id%3D%22swfObjID%22+type%3D%22application/x-shockwave-flash%22+width%3D%22640%22%3E%3Cparam+name%3D%22allowScriptAccess%22+value%3D%22always%22+/%3E%3Cparam+name%3D%22movie%22+value%3D%22papaspizzeria_coolmath_update.swf%22+/%3E%3Cparam+name%3D%22menu%22+value%3D%22false%22+/%3E%3Cparam+name%3D%22quality%22+value%3D%22high%22+/%3E%3Cparam+name%3D%22wmode%22+value%3D%22direct%22+/%3E%3C/object%3E&st=e%3DAIHE3cDmwuY8qdSKfHc6Fp2PRwVwQncsu0PwlCwykRSTvNeh6la67EFZAbfgqxcLPMv%252FVR57aVkCqc0BIZEpI58TLrBVkqDcm%252BAdTFoNuq8suZNlRXX6n366ikUv8s0gxtuZQzZsxXsb%26c%3Denterprise&rpctoken=5143875363914221640"></iframe>-->

<object xmlns="http://www.w3.org/1999/xhtml" data="{{ cdn_url_1 }}" height="480" id="swfObjID" type="application/x-shockwave-flash" width="640">
    <param name="allowScriptAccess" value="always">
    <param name="movie" value="{{ cdn_url_1 }}">
    <param name="menu" value="false">
    <param name="quality" value="high">
    <param name="wmode" value="direct">
</object>

<p>
    <br> Instructions
    <br> To start the game just click on the"save slot" cards. I had the name entry disabled so no one can get creative with the names! ;-)
    <br> It gets hard when there is more than one customer to deal with at once!
    <br> It gets hard when there is more than one customer to deal with at once and watch out for the food critic!
    <br>
</p>

<br>
<a href="{{ cdn_url_1 }}" download class="btn btn-outline-dark">Download 1</a>
<br><br>
<a href="{{ cdn_url_2 }}" download class="btn btn-outline-dark">Download 2</a>
