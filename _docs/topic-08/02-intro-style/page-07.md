---
title: Styling Lists
module: topic-08
permalink: /topic-08/basic-styling-lists/
---

<div class="divider-heading"></div>

Lists can be styled like most text-based block elements, like headings and paragraphs. You can style the list as a whole (`<ul>`, `<ol>`) and/or the list items inside (`<li>`).


## Adding a Background Color
If you want your lists to stand out from other page contents, you can use the **background-color property** to color behind the list, list items, or both.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
ul {
  background-color: lightgrey;
}
li {
  background-color: green;
}
```


## Coloring Text
Just like with other text elements, you can add the **color property** to the list items.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
li {
  color: red;
}
```


## Aligning Horizontally

<p><span class="remember-text">Remember?</span><br/>
Lists and list items are <a href="../../topic-05/extra-markup#block-level" target="_blank">block-level elements</a>, meaning each will get a full-page line all to themselves.</p>


 This can be problematic if you want to do a list of links to your site pages. Without extra styling, they will appear vertically down the page, a design layout that isn't often done. We can change this appearance using the **display property**, set to `inline`.

 <div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
 li {
   display: inline;
 }
 ```


 <div class="divider-pg"></div>


### Example
See how you can make a list stand-out by changing its **background color**, text **color**, and item **display**!

**Note** In the style element, the `ul` and the `li` are put together so that they both use the _display:inline_ style.  Otherwise, the list items won't be horizontal.

<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="NWrqqVy" data-default-tab="html,result" data-user="retrog4m3r" data-pen-title="Basic HTML List Stying" class="codepen"></p>
</div>
