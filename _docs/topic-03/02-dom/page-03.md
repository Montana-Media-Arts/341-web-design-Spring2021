---
title: Choosing and Using HTML
module: topic-03
permalink: /topic-03/dom-html/
categories: html
tags: elements, markdown, paragraph, tags
---

<div class="divider-heading"></div>


This course teaches HTML as its primary markup language because it is widely-used and easy to learn. Using HTML does not mean you cannot implement XHTML standards, like those we provide throughout the course.

These include:
- **Mandatory Structure** - Elements like the `!DOCTYPE` declaration and `<head>` and `<body>` elements are required.
- **Properly Nested Tags** - Tag order is maintained when nesting elements within other elements.
- **Closed Elements** - Elements must always be closed, i.e. `<p>...</p>`. This includes empty elements, i.e. `<br />`.
- **Lowercase Elements and Attributes** - All elements and their attributes must be lowercase, i.e., `<body>` not `<BODY>`.

Don't worry if this doesn't make much (or any) sense right now. Just know that we are teaching HTML with the intent that your sites work at the highest-performance possible without having to learn XHTML to its fullest.


<div class="divider-pg"></div>


## HTML

<div class="row">
  <div class="col-lg-8">
    <p>The most widely-used markup language is HTML or <b>HyperText Markup Language.</b> Files ending in an <code>.html</code> file extension are HTML files, so a <code>page.html</code> is a text file written in HTML.</p>

    <p>HTML is the standard markup language for creating web pages and web applications. Web browsers use HTML to interpret and compose text, images, and other material into visual or audible web pages.</p>

    <p>HTML was first proposed in 1990 by Tim Berners-Lee, then a contract physicist at <a href="https://home.cern/topics/birth-web" targe="_blank">CERN</a>.</p>
  </div>
  <div class="col-lg-4">
    <img src="../img/berners-lee.png" alt="Tim Berners-Lee" title="Tim Berners-Lee" style="max-width: 250px; margin-top: 0;"/>
    <p class="img-caption">Berners-Lee (1955 - )</p>
  </div>
</div>


<div class="divider-pg"></div>


## Elements and Tags
HTML **elements** are small blocks whose beginnings and endings are set by **tags**.


### Elements
An HTML document is composed of a tree of HTML elements. An **element** is an individual component of an HTML document. Elements denote to the processor structure and semantic meaning of the document. Elements may also be nested or encapsulated within other elements.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p>This is a paragraph element.</p>
<p>This is another paragraph element.</p>
`"

Compare this to Markdown:

<div class="code-heading">
  <span class="md">Markdown</span>
</div>
```markdown
This is a paragraph.

This is another paragraph.
`"


### Tags
Tags identify elements in a document. A **tag** is code that is syntactically unique from the text content of the document. In HTML, all tags include a less-than (**<**) and greater-than (**>**) sign, with the tag typed between the two.

<div class="row callout-columns status-info">
  <div class="col-lg-3">
    <div class="icon">
      <ul class="bursts">
        <li class="deg0"></li>
        <li class="deg36"></li>
        <li class="deg72"></li>
        <li class="deg108"></li>
        <li class="deg144"></li>
        <li class="deg180"></li>
        <li class="deg216"></li>
        <li class="deg252"></li>
        <li class="deg288"></li>
        <li class="deg324"></li>
      </ul>
      <i class="fas fa-info-circle"></i>
    </div>
  </div>
  <div class="col-lg-9">
    <p>General formula for an HTML element:</p>
    <p><code>&lt;tagname&gt;</code>...content...<code>&lt;/tagname&gt;</code></p>
  </div>
</div>

Most elements include an "opening" and "closing" tag that the processor uses to identify that element's beginning and end. Closing tags are identical to opening tags, except that they contain a forward-slash (**/**) between the less-than (**>**) sign and the tag text.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p>This is a paragraph element.</p>
<p>This element is created with an opening "<p>" tag and a closing "</p>" tag. We call this "wrapping."</p>
`"

Compare this to Markdown:

<div class="code-heading">
  <span class="md">Markdown</span>
</div>
```markdown
This is a paragraph.

In markdown, paragraphs require no extra markup to signify it as such. An empty line between text blocks represents a new paragraph.
`"
