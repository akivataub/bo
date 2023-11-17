---
layout: game
title: Doom
folder: games/dooms/Doom
gamefile: doom.swf
download: false
description: 
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<h3>DOS-BOX version</h3>
<hr>
<iframe class="dosbox_iframe" allowfullscreen="false" src="../../../dosbox/?soft=DOOM" width="800" height="494"></iframe>

<br>
<hr>
<h3>Flash version</h3>
<hr>

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="800" height="494" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">

<br>
<a href="{{ cdn_url }}" download class="btn btn-outline-dark">Download</a>
<br>
