---
title: Dropdown Menus
module: topic-12
permalink: /topic-12/nav-menu-dropdown/
---

<div class="divider-heading"></div>

The display property can also be used to “hide” elements. At first, it may seem difficult to understand why it would be useful to hide an element, but this is done often in order to create "dropdown menus" or "hidden tips" type content.

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

The following code is one solution to creating a horizontal menu with a dropdown. Notice in line 33, that the content is hidden. Lines 47-49, cause the menu to be displayed, and lines 32-62 are used to present and style the dropdown menu.

Please study the following code to understand it better. You should also download the code and play with it via the links under the example.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="RwRybWr" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Dropdown Menu" class="codepen"></p>
</div>
