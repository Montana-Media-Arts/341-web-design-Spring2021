---
title: HTML Canvas
module: topic-13
permalink: /topic-13/html5-canvas/
categories: development
tags:
---

<div class="divider-heading"></div>


**What is HTML Canvas?**

With all those features, the most exciting is the canvas.  It removed the necessity of having Flash and removes the security vulnerabilities of the past.

The HTML `<canvas>` element is used to draw graphics, on the fly, via JavaScript.

The `<canvas>` element is only a container for graphics. You must use JavaScript to actually draw the graphics.

Canvas has several methods for drawing paths, boxes, circles, text, and adding images.

**Canvas Examples**

A canvas is a rectangular area on an HTML page. By default, a canvas has no border and no content.

The markup looks like this:

```html
<canvas id="myCanvas" width="200" height="100"></canvas>
```

**Note:** Always specify an id attribute (to be referred to in a script), and a width and height attribute to define the size of the canvas. To add a border, use the style attribute.

