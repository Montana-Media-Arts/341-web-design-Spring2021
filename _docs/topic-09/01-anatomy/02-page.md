---
title: Elements and Rules
module: topic-09
permalink: /topic-09/multi-selectors/
---

<div class="divider-heading"></div>

**Rules** can be applied singularly or to one or more selectors:

<span class="label label-info">NOTE:</span> CSS is not whitespace dependent. In other words, one does not need to include extra lines between rules. However, this shown style increases readability of one's code. _It's polite._


### Multiple Selectors with Different Rules

When applying different rules to elements, simply write another selector/declaration set. The closing **curly bracket** (`}`) tells the browser the rule is finished.

<div class="code-heading">
  <span class="css">CSS</span>
</div>

```css
/* Rule 1: Applied to all h1 elements. */
h1 {
    /* Style declarations go here. */
}

/* Rule 2: Applied to all paragraphs. */
p {
    /* Style declarations go here. */
}
```


### Multiple Selectors with the Same Rules

If one needs to apply the same rules to more than one element, they can select multiple elements in a single style rule. To do so, separate each selector element with a comma (`,`).

One can apply additional, unique style rules to an already styled element. These rules are cumulative.

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
h1, h2, p {
    /* Style rules applied to all h1, h2, and paragraph elements. */
}

p {
    /* Additional style rules applied only to paragraph elements. */
}
```
