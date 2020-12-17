---
title: Nobody Likes Rude Code
module: topic-05
permalink: /topic-05/writing-code/
categories: development
tags: best-practice, code
---

<div class="divider-heading"></div>

<div class="container-row">
  <p>It may seem ridiculous or silly, but there's such a thing as being a respectful dev that writes clean, proper code.</p>

  <img src="../img/nedry.gif" alt="Dennis Nedry gif from Jurassic Park" title="Ah ah ah!" style="float: right; width: 150px; margin-top: 0;" onmouseover="PlaySound( 'mySound') " onmouseout="StopSound( 'mySound') "/>

  <p>What does this look like? Well, a site with well-written markup will have:</p>

  <ol>
    <li>Logical or Liner Ordering</li>
    <li>Properly Nested Tags</li>
    <li>Indented Elements</li>
  </ol>

  <p>There are many other unspoken rules you can Google, but those three are my major pet peeves when done poorly - <i>and I'm likely to call you out on them.</i></p>


  <audio id="mySound" loop>
    <source src="../media/nedry.wav" type="audio/wav">
    <source src="../media/nedry.mp3" type="audio/mpeg">
    <source src="../media/nedry.ogg" type="audio/ogg">
    Your browser does not support the audio tag.
  </audio>
  <audio id="mySound" src="../media/nedry.mp3"></audio>

    <script type="text/javascript ">
      function PlaySound(soundobj) {
        var thissound = document.getElementById(soundobj);
        thissound.play();
        thissound.volume = 0.2;
      }

      function StopSound(soundobj) {
        var thissound = document.getElementById(soundobj);
        thissound.pause();
        thissound.currentTime = 0;
      }
    </script>
</div>
