---
title: Styling
module: topic-06
permalink: /topic-06/table-style/
---

<div class="divider-heading"></div>

We can also add visual interest to tables to help with easier reading and showcasing of data. We do this with the **style element**.

In the [Last topic](../../topic-05/head-style), we looked at adding _style_ to HTML in the document's `<head>`, via the `<style>...</style>` element.

We can reference the individual elements of the table as a group for easier styling. We do this by separating the elements by commas in the same line of code. Everything in this string will be affected by the styling described between `{}`.

<span class="label label-info">NOTE:</span> This is something you'll do in much greater detail in a stylesheet when we get to CSS.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<head>
  <style>
      table, th, td {
        /* Attributes that will "decorate" the table: */
      }
  </style>
</head>

<body>
  <table>
    <!-- Table contents to-be-styled: -->
  </table>
</body>
```
