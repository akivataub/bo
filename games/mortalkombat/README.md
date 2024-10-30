---
layout: game
title: Mortal Kombat
folder: games/mortalkombat
gamefile: mortal-kombat.swf
download: true
description: "Mortal Kombat is a game where you fight other characters."
---

{% assign cdn_url = site.cdn | append: "/" | append: page.folder | append: "/" | append: page.gamefile %}

<embed src="{{ cdn_url }}" flashvars="" base="" quality="high" allowscriptaccess="always" allowfullscreen="true" bgcolor="" wmode="window" width="600" height="313" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer">
<br>
<div class="row justify-content-center">
    <div class="col-auto">
        <table border="1" bordercolor="#666666" cellpadding="2" cellspacing="0" style="font-family:Verdana;border-collapse:collapse">
            <tbody>
                <tr>
                    <td style="font-size:13.6px" width="125px">
                        <div align="center"><strong>Game Controls<br></strong><img height="47" src="{{ "/images/joystick-controls.gif" | relative_url }}" width="40">
                        </div>
                    </td>
                    <td style="font-size:13.6px" width="325px">Arrow keys to move<br>A - punch<br>S - block<br>D - Kick
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
</div>
