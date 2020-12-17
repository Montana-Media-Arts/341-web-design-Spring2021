---
title: Definitions
module: topic-05
permalink: /topic-05/definitions/
categories: html
tags: define, elements
---

<div class="divider-heading"></div>

The first use of a new term in a document usually warrants a **definition** tag, `<dfn>`.

The nearest parent of the `<dfn>` tag must also contain the definition/explanation for the term inside the definition tag. Definition tags also link to a related list of terms elsewhere on the page or site.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p>The definition element <def title="definition of term">term</def> is a common way of defining terms.</p>
```


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="gOrBLoo" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="Semantic HTML, Definition" class="codepen"></p>
</div>


<span class="label label-success">Neat-O</span> Hover your mouse over the terms to see their definitions expanded.
