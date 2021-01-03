---
title: HTML5 Draw Images
module: topic-14
permalink: /topic-14/html5-draw-images/
categories: development
tags:
---

Draw Image
<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
var img = document.getElementById("scream");
ctx.drawImage(img, 10, 10);
</script>