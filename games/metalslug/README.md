---
layout: game
title: Metal Slug Flash
folder: games/metalslug
gamefile: metalslugflash.swf
download: true
description: "Metal Slug Flash is a game where you play as a soldier and shoot other soldiers."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" wmode="window" width="600" height="500" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">

<div class="row justify-content-center">
    <div class="col-auto">
        <table border="1" bordercolor="#666666" cellpadding="2" cellspacing="0" style="font-family:Verdana;border-collapse:collapse">
            <div align="center">
                <tbody>
                    <tr>
                        <td style="font-size:13.6px" width="125px">
                        <div align="center"><strong>Game Controls<br></strong><img height="47" src="{{ "/images/joystick-controls.gif" | relative_url }}" width="40"></div>
                        </td>
                        <td style="font-size:13.6px" width="325px">Once the game has loaded use the mouse to click the buttons on the screen to select the difficulty (in Japanese).&nbsp;<br> Keys are:&nbsp;
                            <br> W A S D are to move and duck<br> J K L are to fire, jump and throw bombs
                        </td>
                    </tr>
                </tbody>
</div>
