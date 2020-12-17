---
title: ...And What You Don't
module: topic-11
permalink: /topic-11/hidden-intro/
---

<div class="divider-heading"></div>

The display property can also be used to 'hide' elements. At first, it may seem difficult to understand why it would be useful to hide an element, but this is done often in order to create "drop-down menus" or "hidden tips" type content.

To hide an element, set the `display` properties value to `none`. To get it to appear, you create a selector made up of the parent container and element in question, with the `:hover` pseudo-class added to the parent.

<div class="code-heading">
  <span class="css">CSS</span>
</div>

```css
.child-class-to-unhide {
    display: none;
}
.parent-container:hover .child-class-to-unhide {
    display: block;
}
```
