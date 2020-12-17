---
title: Paragraphs
module: topic-04
permalink: /topic-04/two-tags-paragraphs/
categories: html
tags: break, elements, markdown, paragraphs, preformatted, tags
---

<div class="divider-heading"></div>

Developers place almost all non-heading text within a paragraph element in a web document. The `<p>` tags define paragraph elements.  Remember paragraph elements are two-tag elements written as `<p>...</p>`.


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

In Markdown, a paragraph requires no extra markup to signify it as such. An empty line between text blocks represents a new paragraph.
```





<div class="divider-heading"></div>

Any text between the paragraph tags `<p>...</p>` belongs to the same paragraph.  Putting text between paragraph tags is the most common way of writing paragraphs in HTML pages.

You'll notice that when using Markdown, empty lines create paragraphs and provide a cushion between one paragraph and the next. HTML does not do this.

With HTML, paragraphs tags create paragraphs, and browsers automatically add cushion above and below paragraph elements.


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="Wgqroy" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="Basic HTML Paragraphs" class="codepen"></p>
</div>





<div class="divider-heading"></div>

By default, browsers remove empty spaces from paragraph element blocks. Browsers mimic this behavior with spaces and extra blank lines too. You need to be aware that you cannot change the output of your rendered HTML code by adding additional spaces or lines unless you code for them; merely pressing the space bar or return does not result in a new space or newline.

You can see this below, where the first several paragraphs display as single lines. Using the **line break**, or the `<br />` tag moves the cursor to the next line within the paragraph element.

<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="qXwEbW" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Paragraphs and Line Breaks" class="codepen"></p>
</div>





<div class="divider-heading"></div>

You can use the **preformatted text** element (`<pre>...</pre>`) to tell a browser to render spaces and text exactly as you've typed.

The `<pre>` tag usually displays the contents between the element in a fixed-width font, typically used for preformatted code or text.


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="QQGWGX" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Paragraphs and Preformatted Text" class="codepen">See the Pen <a href="https://codepen.io/Media-Ed-Online/pen/QQGWGX/"></p>
</div>
