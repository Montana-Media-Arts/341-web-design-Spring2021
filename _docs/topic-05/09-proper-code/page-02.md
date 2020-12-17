---
title: 1. Logical or Linear Ordering
module: topic-05
permalink: /topic-05/ordering/
categories: development
tags: best-practice, code, organize
---

<div class="divider-heading"></div>

Most languages read and process top-to-bottom, so it's vital to list them linearly or logically down the page.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>

<html>
  <body>

    <!-- This is improper ordering of blocks! -->
    <!-- The footer should come after the main content. -->
    <footer>
      <p>(C) School of Media Arts</p>
    </footer>

    <main>
      <h1>"Old Town Road"</h1>
      <h2>Yeah, I'm gonna take my horse to the old town road.</h2>
      <i>Lil Nas X</i>
    </main>

  </body>
</html>
```
