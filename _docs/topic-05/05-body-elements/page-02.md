---
title: Structural Markup
module: topic-05
permalink: /topic-05/structural-markup/
categories: html
tags: markup, structural
---

<div class="divider-heading"></div>

**Structural markup** embeds _information_ about the structure of a document. Structure includes elements such as:

- Headings
- Paragraphs
- Breaks
- Lists

These elements will help guide a user visually and provide information about the type of content through a document. These elements are also used by the browser and the DOM to understand the content of the document. A browser uses this structural markup to assist [screen readers](http://www.afb.org/prodBrowseCatResults.aspx?CatID=49) and other accessibility-based software.

<p><span class="remember-text">Remember?</span><br/>
The most basic of structured documents should include tags identifying headings and paragraphs. These two markup elements are used in almost every document editing application and are crucial in authoring web content.</p>



## Headings and Paragraphs
You are already familiar with headings, paragraphs, and breaks.

**Headings** are defined with the `<h1>` to `<h6>` tags, where `<h1>` describes the most crucial heading and `<h6>` defines the least important heading. `<h1>` headings are considered to be _Main Headings_, while `<h2>` headings are usually considered _sub-headings_ and so forth through `<h6>`.

Any text between the **paragraph** tags `<p>...</p>` belongs to the same paragraph. Almost all non-heading text will be placed within a paragraph element in a web document.


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="MWyPbbx" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="HTML Structural Body Elements" class="codepen"></p>
</div>
