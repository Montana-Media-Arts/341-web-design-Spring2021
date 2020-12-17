---
title: Pseudo-Selectors
module: topic-10
permalink: /topic-10/pseudo-selectors/
---

<div class="divider-heading"></div>

CSS includes a number of quasi-operations for things called **pseudo-selectors**. Pseudo-selectors don't select elements per-say, but rather certain parts of elements, or elements in certain contexts.

Pseudo-elements allow for the selection of content, as if it were a separate element, without having to mark it up as such in the HTML.

There are two main types of pseudo-selectors:
- pseudo-elements (`selector::keyword`)
- pseudo-classes (`selector:keyword`)

<div class="code-heading">
  <span class="css">CSS</span>
</div>

```css
/* Pseudo-element selector example: */
p::first-letter {}

/* Pseudo-class selector example: */
p:hover {}
```
<span class="label label-info">NOTE:</span> Pseudo-elements are preceded by double colons, as opposed to a single colon like with pseudo-classes.

You encounter pseudo-selections daily, particularly with links. If a link changes color [when you interact with it](../../), its states (like `:hover`) have been set in the site's styling.
