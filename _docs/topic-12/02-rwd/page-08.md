---
title: Responsive iframes
module: topic-12
permalink: /topic-12/rwd-iframes/
categories: development
tags:
---

<div class="divider-heading"></div>

## Responsive iframes


The goal is to create an iframe that will keep the aspect ratio (4:3, 16:9, etc.) when resized.

### What is aspect ratio?

The aspect ratio of an element describes the proportional relationship between its width and its height. Two common video aspect ratios are 4:3 (the universal video format of the 20th century), and 16:9 (universal for HD television and European digital television, and for YouTube videos).


Use a container element, like <div>, and add the iframe inside of it:

```html
<div class="container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/V1bFr2SWP1I"></iframe>
</div>
```

Add a percentage value for padding-top to maintain the aspect ratio of the container `div`. The following example will create an aspect ratio of 16:9, which is the default aspect ratio of YouTube videos.

```css
.container {
  position: relative;
  overflow: hidden;
  width: 100%;
  padding-top: 56.25%; /* 16:9 Aspect Ratio (divide 9 by 16 = 0.5625) */
}

/* Then style the iframe to fit in the container div with full height and width */
.responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
}
```

For 4:3 Aspect Ratio

```css
.container {
  padding-top: 75%; /* 4:3 Aspect Ratio */
}
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="RwRYmBm" data-default-tab="result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Responsive iframes" class="codepen"></p>
</div>

<a href="https://www.w3schools.com/howto/howto_css_responsive_iframes.asp" target="_new"><em>Reference</em></a>