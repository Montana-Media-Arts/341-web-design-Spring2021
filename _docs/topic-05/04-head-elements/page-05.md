---
title: Link
module: topic-05
permalink: /topic-05/head-link/
categories: html
tags: elements, head, link
---

<div class="divider-heading"></div>

The _link_ element tells a browser about other resources that the page may need to load. Typically, these are the **CSS** or “stylesheets” which dictate how a page will appear in a browser.

We will not use this element for the first few weeks but will rely upon it for the remainder of the semester after starting with CSS.

<span class="label label-info">Note</span> This element only requires an opening tag, as the element contains all the attributes within the opening tag. `link` is another example of an **empty element.**


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Other meta elements -->
    <link rel="stylesheet" href="./css/style.css">

  </head>

</html>
```
