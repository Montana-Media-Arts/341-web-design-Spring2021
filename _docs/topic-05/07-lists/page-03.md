---
title: Unordered
module: topic-05
permalink: /topic-05/unordered-lists/
categories: html
tags: list, unordered
---

<div class="divider-heading"></div>

**Unordered lists** begin with dots, bullets, dashes, or other visual signifiers. These lists are great for things like ingredients in a recipe. Unordered lists, by default, get a dot in most browsers.

<table style="width: 75%; margin: auto;">
<tbody>
  <tr>
    <td style="border: none;">
      <ul style="list-style-type:disc">
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
      </ul>
    </td>
    <td style="border: none;">
      <ul style="list-style-type:square">
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
      </ul>
    </td>
    <td style="border: none;">
      <ul style="list-style-type:circle">
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
      </ul>
    </td>
  </tr>
</tbody>
</table>


To identify an unordered list, the content is contained within the unordered list tags ( `<ul>...</ul>` ).

As with the ordered list, contain each list item within a list item element ( `<li>...</li>` ).


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<ul>
  <li>List Item</li>
  <li>List Item</li>
  <li>Etc...</li>
</ul>
```


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="dyMgOjW" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="HTML Unordered Lists" class="codepen"></p>
</div>
