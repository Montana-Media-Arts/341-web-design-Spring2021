---
title: Adding Content
module: topic-03
permalink: /topic-03/page-content/
categories: development
tags: elements, guide
---

<div class="divider-heading"></div>


Once you become familiar with the notion that HTML elements are comprised of HTML tags, adding these elements to stardard documents is not difficult. Remember that anything you want a browser to render _must_ be created withing the `<body>` element:

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<body>
  <p>I am a paragraph element in the body.</p>
  <p>I am another paragraph element, also in the body.</p>
</body>
```

Fortunately, the structure is fairly universal between text documents. Let's look at  **headings** and **paragraphs** as examples.


## Headings in HTML
Headings are defined with the `<h1>` to `<h6>` tags, and their elements are written as `<h1>...</h1>`.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<h1>This is a Heading 1</h1>
```

Compare this to Markdown:

<div class="code-heading">
  <span class="md">Markdown</span>
</div>
```markdown
# This is a Heading 1
```


<div class="divider-pg"></div>


## Paragraphs
Place almost all non-heading text within a paragraph element in a web document. Define paragraphs with the `<p>` tags, and the element written as `<p>...</p>`.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p>This is a paragraph element.</p>
```

Compare this to Markdown:

<div class="code-heading">
  <span class="md">Markdown</span>
</div>
```markdown
This is a paragraph.

In markdown, a paragraph requires no extra markup to signify it as such. An empty line between text blocks represents a new paragraph.
```
