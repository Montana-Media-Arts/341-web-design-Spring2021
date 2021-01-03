---
title: HTML5 Text
module: topic-14
permalink: /topic-14/html5-text/
categories: development
tags:
---

<div class="divider-heading"></div>


Draw a Text
Example
<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.font = "30px Arial";
ctx.fillText("Hello World", 10, 50);
</script>
Stroke Text
Example
<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.font = "30px Arial";
ctx.strokeText("Hello World", 10, 50);
</script>