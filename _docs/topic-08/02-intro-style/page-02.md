---
title: The Style Element
module: topic-08
permalink: /topic-08/basic-style-element/
---

<div class="divider-heading"></div>

To continue the review, let's revisit the **style element**, located in the `<head>` of an HTML document.

<p><span class="remember-text">Remember?</span><br/>
The style element establishes simple style definitions for in a single HTML page without linking to external documents (e.g. main.css).</p>


We will get into using the method later on, but you should consider the facts of styling this way:

<ul style="list-style-type: none">
  <li class="icon-pro"> Benefit: All styling for a page is done within the same page.</li>
  <li class="icon-con"> Problem: To apply the same styles on different pages requires manual addition or copying on all pages of the site.</li>
</ul>

<span class="label label-danger">Important</span> On the following pages you will be given styling options to explore. Just remember that any code you use or copy **has to be added inside the page's** `<head>` **element**.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Way-Cool Awesome Site</title>
    <style>
      /* “Decorative” styling of page contents... */
    </style>
  </head>

  <body>
    <!-- Page contents that will get styled... -->
  </body>
</html>
```


<div class="divider-pg"></div>


## Adding Style to Page Contents

### Selecting Elements (“Apply to _all elements_ on my page.”)
**Selecting elements** effects large portions of the page, good for backgrounds, image styling, and text, but not for specific instances.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<style>
  body {
    /* Will affect the ENTIRE body of the page. */
  }
  h1 {
    /* Will affect EVERY heading 1 on the page. */
  }
  img {
    /* Will affect ALL images on the page. */
  }
</style>
```

### Example 1

We can apply styles to all elements on a page by specifying the element in the style tag.

For example, we can say we want _all_ divisions in our site to have black borders, a font of Tahoma and a size of 12 px.
- element selector: `div` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(“Do _____ to ALL divs on the page.”)


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="bGedNXp" data-default-tab="html,result" data-user="retrog4m3r" data-pen-title="Basic Style Selectors in HTML" class="codepen"></p>
</div>
