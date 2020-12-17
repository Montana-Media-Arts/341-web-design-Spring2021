---
title: Quotes and Blockquotes
module: topic-05
permalink: /topic-05/quote-blockquote/
categories: html
tags: blockquote, elements, quote
---

<div class="divider-heading"></div>

There are two common ways of marking up quotations in HTML: quote (`<q>...</q>`) and blockquote (`<blockquote>...</blockquote>`).

The **quote** tag defines a short quotation. Browsers normally _insert quotation marks_ around the quotation.

The **blockquote** tag specifies a section quoted from another source. Browsers usually _indent_ blockquote elements.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<q>This is an quote element, good for keeping quotes inline with other paragraph text.</q>

<blockquote>
  Sometimes a quote spans multiple sentences or lines.<br/>
  Longer quotes are better served in a blockquote element.
</blockquote>
```


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="GRZYNMO" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="Semantic HTML, Quotes and Blockquotes" class="codepen"></p>
</div>
