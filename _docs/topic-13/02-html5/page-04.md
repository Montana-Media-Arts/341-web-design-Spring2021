---
title: HTML5 Text
module: topic-13
permalink: /topic-13/html5-text/
categories: development
tags:
---

<div class="divider-heading"></div>

Continuing on this path of making objects appear on the canvas, we can also add text.

**Draw a Text**

```js
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.font = "30px Arial";
ctx.fillText("Hello World", 10, 50);
```


**Stroke Text**

```js
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.font = "30px Arial";
ctx.strokeText("Hello World", 10, 50);
```