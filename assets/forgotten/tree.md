---
layout: none
---

<style>
  body {
    background-color: #000000;
  }
</style>

<div style="display: flex; height: 100vh; justify-content: center; align-items: center;">
  <img src="./tree.gif">
  
  <script>
    const music = document.getElementById("music");

    document.getElementById("start").addEventListener("click", () => {
        music.play();
    });
  </script>

  <br>
  <a href="./">Go Back</a>
</div>

<audio id="music" loop>
  <source src = "./man.mp3" type= "audio/mpeg">
  Your browser does not support the audio element.
</audio>
