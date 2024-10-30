---
layout: game
title: "Gameboy"
folder: games/gameboy
gamefile: gameboy.js
description: "Made with: gameboy.js"
download: false
---
<div id="container">

<div class="canvas-container"><canvas id="canvas">Your browser does not seem to support canvas.</canvas></div>

<p class="commands">
    <button onclick="g.pause(true);" class="btn">Pause</button>
    <button onclick="g.pause(false);" class="btn">Run</button>
</p>
<p class="commands">
    <label><input id="sound-enable" type="checkbox" onchange="g.setSoundEnabled(this.checked);" /> Enable sound
        (experimental)</label>
</p>
<p class="commands">
    <label>
        Screen zoom
        <select id="screen-zoom" onchange="g.setScreenZoom(this.value);">
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
        </select>
    </label>
</p>
<p>
    <span id="status"></span> <span id="game-name"></span>
</p>
<p id="error" class="hide"></p>

<div class="rom-section">
    <div id="rom-file">
        <label>Choose a ROM file on your computer: <input class="btn" type="file" id="file" /></label>
    </div>

    <div id="rom-drop">
        <div id="dropzone">
            <p>
                Or drop a ROM file here
            </p>
        </div>
    </div>
</div>

<div id="keyboard-info" style="text-align:center;">
    <p>Current keyboard mapping:</p>
    <table align="center">
        <thead>
            <tr>
                <th>Gameboy pad</th>
                <th>Keyboard mapping</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>A</td>
                <td>G</td>
            </tr>
            <tr>
                <td>B</td>
                <td>B</td>
            </tr>
            <tr>
                <td>START</td>
                <td>H</td>
            </tr>
            <tr>
                <td>SELECT</td>
                <td>N</td>
            </tr>
            <tr>
                <td>Directional pad</td>
                <td>Arrow keys</td>
            </tr>
        </tbody>
    </table>
</div>

</div>

<script type="text/javascript" src="gameboy.js"></script>

<script type="text/javascript">
// configuration
var opts = {
    romReaders: [
        new GameboyJS.RomFileReader(),
        new GameboyJS.RomDropFileReader(document.getElementById('dropzone')),
        //new GameboyJS.RomFileReader('Pokemon-Red-Version.gb')
    ]
};
var g = new GameboyJS.Gameboy(document.getElementById('canvas'), opts);
g.setSoundEnabled(document.getElementById('sound-enable').checked);
g.setScreenZoom(document.getElementById('screen-zoom').value);
</script>

<br>
<br>
<p>Made with: <a href="https://github.com/juchi/gameboy.js" target="_blank">gameboy.js</a></p>
