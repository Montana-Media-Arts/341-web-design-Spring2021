---
title: Ordered
module: topic-05
permalink: /topic-05/ordered-lists/
categories: html
tags: list, ordered
---

<div class="divider-heading"></div>

**Ordered lists** are where an ascending identifier, such as numbers, letters, or Roman numerals, prepends each entry.

<table style="width: 75%; margin: auto;">
<tbody>
  <tr>
    <td style="border: none;">
      <ol type="1">
        <li>Lather</li>
        <li>Rinse</li>
        <li>Repeat</li>
      </ol>
    </td>
    <td style="border: none;">
      <ol type="A">
        <li>Lather</li>
        <li>Rinse</li>
        <li>Repeat</li>
      </ol>
    </td>
    <td style="border: none;">
      <ol type="I">
        <li>Lather</li>
        <li>Rinse</li>
        <li>Repeat</li>
      </ol>
    </td>
  </tr>
</tbody>
</table>

Surrounding content by ordered list tags identifies a list.
( `<ol>...</ol>` )

Each “list item” must be surrounded by the list item tags. ( `<li>...</li>` ).


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<ol>
  <li>List Item</li>
  <li>List Item</li>
  <li>Etc...</li>
</ol>
```


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="BaKqQVP" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="HTML Ordered Lists" class="codepen"></p>
</div>
