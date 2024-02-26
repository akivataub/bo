---
layout: game
title: Galaga
folder: games/galaga
gamefile: galaga.swf
download: true
description: "Galaga is a classic arcade game from the 80s. The goal is to get the spaceship across the screen without getting hit by an alien."
---


{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" wmode="window" width="430" height="500" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">

<br>
<br>
<div align="center">
    <div class="row justify-content-center">
        <div class="col-auto">
            <table border="1" bordercolor="#666666" cellpadding="2" cellspacing="0" style="text-align:center;font-family:Verdana;border-collapse:collapse">
                <tr>
                    <td style="font-size:13.6px" width="125px">
                        <div align="center"><strong>Game Controls<br></strong><img height="47" src="{{ "/images/joystick-controls.gif" | relative_url }}" width="40">
                        </div>
                    </td>
                    <td style="font-size:13.6px" width="325px">Spacebar to shoot.<br> Arrow keys to move.</td>
                </tr>
            </table>
        </div>
    </div>
</div>
