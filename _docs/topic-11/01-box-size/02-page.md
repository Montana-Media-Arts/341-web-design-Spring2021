---
title: The Box Model
module: topic-11
permalink: /topic-11/box-model/
---

<div class="divider-heading"></div>

<img src="../img/box-model-full.gif" alt="the full css box model" style="width: 350px; margin: 0 auto 30px;" />

To begin, we create "boxes" by setting a specified width and height. But setting an area with only these properties will give us a space to contain content (say color or text) so-wide by so-high, but little else. We cannot control placement, cushion, or relationship to other boxes without giving the stylesheet more information.

Luckily, there's pretty standard CSS template for getting started:

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
.my-box {
  width: ;
  height: ;
  border: ;
  padding: ;
  margin: ;
}
```

This template is known as the “<b><a href="https://www.w3schools.com/css/css_boxmodel.asp" target="_blank">Box Model.</a></b>” In HTML and CSS, we imagine elements as boxes with certain properties. Specifically, every block element in HTML has a **border**, **padding**, and **margin**.

We will go over the tricks and trades of the “box model” over this topic, as well as other techniques you can use to control the appearance of your content.
