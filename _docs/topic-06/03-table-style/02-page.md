---
title: Borders
module: topic-06
permalink: /topic-06/table-borders/
---

<div class="divider-heading"></div>

## Borders

By default, a table is rendered without borders. Using the code snippet below, the table outline, heading coloums and rows, and cells will all be given a **border**.

A `border=""` attribute is broken-up into 3 componets: width, style, and color. We will get more into borders with CSS, so for now, this is the basic border styling for tables.

This style element effectively states _"a border 1 pixel wide, drawn as a solid line, in black."_

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<style>
    table, th, td {
      border: 1px solid black;
    }
</style>
```


<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="JjXzypy" data-default-tab="html,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Tables - Borders" class="codepen"></p>
</div>


<span class="label label-info">NOTE:</span> If you want only _one_ line between your cells, you can use the `border-collapse` property. See the “Code-Play” linked in the next &nbsp;<i class="fa fa-check-square-o" aria-hidden="true"></i> **TODO**.
