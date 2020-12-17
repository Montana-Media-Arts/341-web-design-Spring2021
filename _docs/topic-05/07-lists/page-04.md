---
title: Definitions
module: topic-05
permalink: /topic-05/definition-lists/
categories: html
tags: definition, list
---

<div class="divider-heading"></div>

**Definition lists** are used to define terms. A definition list is identified with `<dl>...</dl>` tags.

The term being defined is encapsulated in "definition term" tags (`<dt>...</dt>`).

The terms definition is then encapsulated in the "definition" tags (`<dd>...</dd>`).

<span class="label label-info">Note</span> Sometimes, you might see a list where there are two terms used for the same definition or two different definitions for the same term. The usage of terms is acceptable.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<dl>
  <dt>Term 1</dt>
    <dd>This is the definition of Term 1.</dd>
  <dt>Term 2</dt>
    <dd>This is the definition of Term 2.</dd>
</dl>
```


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="MWyPbBN" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="HTML Definition Lists" class="codepen"></p>
</div>
