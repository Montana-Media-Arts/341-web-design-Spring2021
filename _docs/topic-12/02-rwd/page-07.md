---
title: Responsive Images
module: topic-12
permalink: /topic-12/rwd-images/
categories: development
tags:
---

<div class="divider-heading"></div>

## Responsive Images

### width property

If the width property is set to a percentage and the height is set to "auto", the image will be responsive and scale up and down.

```css
img {
  width: 100%;
  height: auto;
}
```

**Note** the image can be scaled up to be larger than its original size. A better solution, in many cases, will be to use the max-width property instead.

### max-width property

If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size.

```css
img {
  max-width: 100%;
  height: auto;
}
```

Experiment with `width` and `max-width`

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="JjKazJq" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Media Queries" class="codepen"></p>
</div>


### Background Images

Background images can also respond to resizing and scaling.

There are three different methods:

If the background-size property is set to "contain", the background image will scale, and try to fit the content area. However, the image will keep its aspect ratio (the proportional relationship between the image's width and height):

```css
div {
  width: 100%;
  height: 400px;
  background-image: url('scissors.png');
  background-repeat: no-repeat;
  background-size: contain;
}
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="gOMBgRr" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="div background-size:contain" class="codepen"></p>
</div>

If the background-size property is set to "100% 100%", the background image will stretch to cover the entire content area.

```css
div {
  width: 100%;
  height: 400px;
  background-image: url('scissors.png');
  background-size: 100% 100%;
}
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="JjKmEJz" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="div background-size:100 100" class="codepen"></p>
</div>

If the background-size property is set to "cover", the background image will scale to cover the entire content area. Notice that the "cover" value keeps the aspect ratio, and some part of the background image may be clipped.

```css
div {
  width: 100%;
  height: 400px;
  background-image: url('scissors.png');
  background-size: cover;
}
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="dyXgNRx" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="div background-size:100 100" class="codepen"></p>
</div>

### Different Images for Different Devices

A large image can be perfect on a big computer screen, but useless on a small device. Why load a large image when you have to scale it down anyway? To reduce the load, or for any other reasons, you can use media queries to display different images on different devices.

Here is one large image and one smaller image that will be displayed on different devices.

```css
/* For width smaller than 600px: */
body {
  background-image: url('scissors_small.png');
}

/* For width 600px and larger: */
@media only screen and (min-width: 600px) {
  body {
    background-image: url('scissors.png');
  }
}
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="gOMdEzg" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Background Images" class="codepen"></p>
</div>


Another option is the choose the device width rather than the width.

```css
/* For devices 600px and larger: */
@media only screen and (min-device-width: 600px) {
  body {
    background-image: url('scissors.png');
  }
}
```

<a href="https://www.w3schools.com/css/css_rwd_images.asp" target="_new"><em>Reference</em></a>