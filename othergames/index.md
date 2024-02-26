---
layout: default
title: Other Games
description: 
---

<div class="search-container">
    <input type="text" id="gameFinder" onkeyup="gameFinder()" placeholder="Search for other games only" title="Type in a game">
    <script>
        function gameFinder() {
            var input, filter, ul, li, a, i, txtValue;
            input = document.getElementById("gameFinder");
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

<div class="OtherGames" id="OtherGames" markdown="1">

{% include_relative README.md %}

</div>
