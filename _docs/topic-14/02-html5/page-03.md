---
title: HTML5 Draw Shapes
module: topic-14
permalink: /topic-14/html-draw-shapes/
categories: development
tags:
---

<div class="divider-heading"></div>


Add a JavaScript
After creating the rectangular canvas area, you must add a JavaScript to do the drawing.

Here are some examples:

Draw a Line
Example
<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(0, 0);
ctx.lineTo(200, 100);
ctx.stroke();
</script>

Draw a Circle
Example
<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.arc(95, 50, 40, 0, 2 * Math.PI);
ctx.stroke();
</script>
