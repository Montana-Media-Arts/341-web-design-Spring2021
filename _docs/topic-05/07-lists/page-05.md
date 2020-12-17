---
title: Nested Lists
module: topic-05
permalink: /topic-05/nested-lists/
categories: html
tags: list, nested, ordered, unordered
---

<div class="divider-heading"></div>

You can combine list types and use multiple **nested list** elements to create hierarchically-related lists. This nesting is particularly useful for outlines or multi-part instructions, as examples.

<span class="label label-info">Note</span> Notice how the nested list is contained _within_ the parent "list-item" element.

```html
<ol id="ordered-list">
  <li>Ordered List Item #1.</li>
  <li>Ordered List Item #2.</li>
      <ul id="unordered-list">
          <li>Item A relating to Order List Item #2.</il>
          <li>Item B relating to Order List Item #2.</li>
      <ul>
  <li>Ordered List Item #3.</li>
  <li>Ordered List Item #4.</li>
  <li>Etc...</li>
<ol>
```


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="RwaeoYj" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="HTML Nested Lists" class="codepen"></p>
</div>
