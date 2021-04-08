---
title: HTML5 Draw Shapes
module: topic-13
permalink: /topic-13/html5-draw-shapes/
categories: development
tags:
---

<div class="divider-heading"></div>


**Add a JavaScript**

After creating the rectangular canvas area, you must add a JavaScript to do the drawing.

Here are some examples:

**Draw a Line**

```js
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(0, 0);
ctx.lineTo(200, 100);
ctx.stroke();
```

**Draw a Circle**

```js
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.arc(95, 50, 40, 0, 2 * Math.PI);
ctx.stroke();
```