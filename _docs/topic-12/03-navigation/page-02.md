---
title: The Nav Bar
module: topic-12
permalink: /topic-12/nav-menu-bar/
---

<div class="divider-heading"></div>

In the HTML module you looked at <a href="../../topic-08/basic-nav-about/" target="_new">navigating to site pages</a> using the **nav element**. There, we created a list of links, perhaps broken up by vertical lines or spacing:

<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="WNxgBMr" data-default-tab="html,result" data-user="retrog4m3r" data-pen-title="HTML Nav Element, Page Navigation" class="codepen"></p>
</div>

This was helpful up to a point, but its very limiting on how we can style these links.By changing the **display** property of those links, we can change how each relates to each other as elements.


Let's review:

## Display
<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
div {
  display: ;
}
```

The CSS `display:` property allows developers to explicitly specify and/or change the display properties for any element, including the option to "hide" an element. This greatly increases the developers ability to create layouts that support the presentation of content in a web browser.

The `display:` property is called on the actual element it is being applied to (as opposed to a parent element holding child elements).

The three main display properties that we'll discuss are:
- `block`
- `inline`
- `inline-block`


### Inline
The `display: inline;` rule forces elements to act like inline elements.  Inline elements, unlike block-level elements:

- only take up as much horizontal space as is needed (ignores `width` properties).
- do not force new lines.
- "flow" with content on the screen, and as such, do not respect the margin property.
- cannot change the vertical (top/bottom) distance between themselves and other elements.


### Inline-Block
The `display: inline-block;` rule, like `display: inline;`, removes new lines inherent in block elements. Unlike `display: inline;`, `display: inline-block;` also forces elements to respect margin and vertical spacing properties/rules.

However, this also means these elements will expand horizontally to fill the parent-container. Therefore, you must _explicitly_ set the width of these elements.


### Block
Just like the display property can be used to turn 'block' elements into `inline` or `inline-block` elements, it can also be used to turn 'inline' elements into `block` elements. This technique is often used to create vertical nav bars out of lists.


<div class="divider-pg"></div>


In the following example, notice that the same basic HTML code is used three times in a row. However, the second and third examples have `display: inline;` & `display: inline-block;`, respectively.

Notice the differences of these display techniques. Particularly with regard to horizontal and vertical spacing.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="XWKEvvP" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="[Topic-09] Display, Pt. 2" class="codepen"></p>
</div>


As you can see, we have used `display: inline;` & `display: inline-block;` to create our first header nav bars! And in fact, it is often used for that purpose.
