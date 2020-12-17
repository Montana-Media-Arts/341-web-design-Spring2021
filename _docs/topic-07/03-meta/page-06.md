---
title: Viewport Element
module: topic-07
permalink: /topic-07/meta-viewport/
---

<div class="divider-heading"></div>

The **viewport** name type tells a browser how to display the page with respect to size, pixel density, and zoom-capabilities. This meta type is critical for websites are mobile device friendly. _You should start setting the viewports meta type in your documents._

The following is the setting you should use for most sites:

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

This tells the browser that the width of the page is intentionally “equal to the width of the device” (i.e. there will be no horizontal scrolling, which users are not accustomed to). It also tells the browser to initially display the page with a scale factor of 1, or no zooming.
