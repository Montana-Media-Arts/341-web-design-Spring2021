---
title: Tables in HTML
module: topic-06
permalink: /topic-06/table-about/
---

<style>
  table, th, td {
    border: 1px solid #ddd;
  }
</style>

<div class="divider-heading"></div>

Tables are used to represent relationships and complex data, such as scores and stats, money markets, databases, etc.

We can use tables to organize less-complex (non-statistical) infomation. Tables can also break up linear information groups; for example, homework step numbers, step details, and step images).

However, once we learn CSS, organizing text-based using stylesheets is better practice. This is primarily because tables can be difficult for accessibility software to translate if done improperly.

The example on the following pages will show this situation, using a simple 2x2 set-up ("2 rows by 2 columns"):

```html
<table style="width: 200px; margin: 40px auto;">
   <tr>
      <th></th>
      <th scope="col">Column A</th>
   </tr>
   <tr>
      <th scope="row">Row 1</th>
      <td>Cell A1</td>
   </tr>
</table>

```
Result:

<table style="width: 200px; margin: 40px auto;">
   <tr>
      <th></th>
      <th scope="col">Column A</th>
   </tr>
   <tr>
      <th scope="row">Row 1</th>
      <td>Cell A1</td>
   </tr>
</table>

