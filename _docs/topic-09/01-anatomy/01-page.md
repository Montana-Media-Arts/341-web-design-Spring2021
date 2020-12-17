---
title: Select and Declare
module: topic-09
permalink: /topic-09/select-declare/
---

<div class="divider-heading"></div>

To "style" content in an HTML document, one must write style "rules" that apply to different elements. These rules always follow the same patterns.

### Selector

The first part of every rule is a "**selector**", which tells the browser what element(s) the rule applies to. This is followed by a space, then a block, surrounded by curly brackets.

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
/* ⬇ SELECTOR - selects all h1 elements */
   h1 { <- need the open curly brace
     // this is the block
   } <- need the closing curly brace
```

### Declaration

The portion of the rule inside of the curly brackets is known as the **declaration**. This tells the browser what to do to the selected element(s).

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
/* ⬇ SELECTOR - selects all h1 elements */
   h1 {
     /* ⬇ DECLARATION goes inside curly brackets. */
       color: white;
   }
```
