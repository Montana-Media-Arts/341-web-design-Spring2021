---
title: Abbreviations and Acronyms
module: topic-05
permalink: /topic-05/abbr-acro/
categories: html
tags: abbreviation, acronym, elements
---

<div class="divider-heading"></div>

The **abbreviation** element (`<abbr>...</abbr>`) defines an abbreviation or an acronym, like "Mr.", "Dec.", "ASAP", "ATM".

Marking up abbreviations can give useful information to browsers, translation systems, and search-engines.

<span class="label label-info">Note</span> Previous to HTML5, there was an `<acronym>` tag that is no longer supported. Is it best practice to use `<abbr>` for both abbreviations and acronyms in HTML5.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p>You can spell out acronyms using the <abbr title=""> tag.</p>

<p>For example, <abbr title="HyperText Markup Language">HTML</abbr>.</p>
```


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="PoNybOQ" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="Semantic HTML, Abbreviations and Acronyms" class="codepen"></p>
</div>


<span class="label label-success">Neat-O</span> Hover your mouse over the shortened words to see their names expanded!
