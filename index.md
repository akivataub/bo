---
layout: home
title: Home
---

<div class="search-container">
    <input type="text" id="gameFinder" onkeyup="gameFinder()" placeholder="Search for games only" title="Type in a game">
    <script>
        function gameFinder() {
            var input, filter, ul, li, a, i, txtValue;
            input = document.getElementById("gameFinder");
            filter = input.value.toUpperCase();
            ul = document.getElementById("Games");
            li = ul.getElementsByTagName("li");
            for (i = 0; i < li.length; i++) {
                a = li[i].getElementsByTagName("a")[0];
                txtValue = a.textContent || a.innerText;
                if (txtValue.toUpperCase().indexOf(filter) > -1) {
                    li[i].style.display = "";
                } else {
                    li[i].style.display = "none";
                }
            }
        }
    </script>
</div>

<div class="Games" id="Games" markdown="1" style="margin-right: 50px;">

## [Games](games/)

{% include_relative games/README.md %}

</div>

---

<div class="search-container">
    <input type="text" id="othergameFinder" onkeyup="othergameFinder()" placeholder="Search for other games only" title="Type in a game">
    <script>
        function othergameFinder() {
            var input, filter, ul, li, a, i, txtValue;
            input = document.getElementById("othergameFinder");
            filter = input.value.toUpperCase();
            ul = document.getElementById("OtherGames");
            li = ul.getElementsByTagName("li");
            for (i = 0; i < li.length; i++) {
                a = li[i].getElementsByTagName("a")[0];
                txtValue = a.textContent || a.innerText;
                if (txtValue.toUpperCase().indexOf(filter) > -1) {
                    li[i].style.display = "";
                } else {
                    li[i].style.display = "none";
                }
            }
        }
    </script>
</div>

<div class="OtherGames" id="OtherGames" markdown="1" style="margin-right: 50px;">

## [Other Games](othergames/)

{% include_relative othergames/README.md %}


<div class="HackedGames" markdown="1" style="margin-right: 50px;">

## Hacked Games

* [Portal the Flash Version<span class="material-icons">launch</span>](http://www.hackedonlinegames.com/game/934)
* [Knighttron<span class="material-icons">launch</span>](http://www.arcadeprehacks.com/game/32862/knighttron.html)
* [Acade Prehacks<span class="material-icons">launch</span>](http://www.arcadeprehacks.com/)
* [Hacked Online Games<span class="material-icons">launch</span>](http://www.hackedonlinegames.com/)

</div>
