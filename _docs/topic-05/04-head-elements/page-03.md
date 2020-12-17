---
title: Viewport
module: topic-05
permalink: /topic-05/head-viewport/
categories: html
tags: elements, head, viewport, meta
---

<div class="divider-heading"></div>

The **viewport** is the user's visible area of a web page. It varies with the device and will be smaller on a mobile phone than on a computer screen.

<img src="../img/meta-viewport.png" alt="two screens, one with viewport set" style="width: 250px;" />

The rise of mobile devices changed how we view and build for the web. HTML5 introduced a method to let web designers take control over the viewport through the meta tag.

You should include the following `<meta>` viewport element in all your web pages:


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Other meta elements -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

  </head>

</html>
```


A `<meta>` viewport element gives the browser instructions on controlling the page's dimensions and scale.

The `width=device-width` part sets the page's width to follow the screen-width of the device (which will vary depending on the device).

The `initial-scale=1.0` part sets the initial zoom level when the browser first loads it.

Include this in your head elements so that your pages display more appropriately on mobile browsers.
