---
title: Processing and the DOM
module: topic-03
permalink: /topic-03/dom-breakdown/
categories: development
tags: dom, processor
---

<div class="divider-heading"></div>


In this topic, we begin looking at “pages,” or the actual visualization of the content in your directories. However, before we make anything, we need to talk about how data gets from your keystrokes to a browser and how that browser renders information for viewing.

For example, HTML is a language that describes the structure of a document intended for viewing through a browser. The browser’s processor identifies _elements_ of the document by looking for _tags_ embedded directly in the text. Then, the **Document Object Model** (DOM) parses these elements.

## What is the DOM?
<div class="row img-text-columns">
  <div class="col-lg-2">
    <img src="../img/dom-map.svg" alt="billboard with the words www.example.com on it" title="Domain" />
  </div>
  <div class="col-lg-10">
    <p>The <b>DOM</b> is an interface to a document and stipulates how that document is accessed and changed by defining its structure in a logical way. The DOM represents these documents as nodes and objects on a <a href="https://en.wikipedia.org/wiki/Tree_structure" target="_blank">tree structure</a> so that programming languages such as <a href="../../topic-01/web-files-scripts/">JavaScript</a> can modify the content.</p>

    <p>This process becomes particularly useful when styling (or “decorating”) objects. Combined with some other processes (see “<a href="../browser-intro">How Web Browsers Function</a>”), the DOM helps connect styling wants to the appropriate structural elements.</p>
  </div>
</div>


## What _isn't_ the DOM?
<div class="row img-text-columns">
  <div class="col-lg-2">
    <img src="../img/dom-inspect.svg" alt="graphic of a person smiling" title="File" />
  </div>
  <div class="col-lg-10">
    <p>The DOM is not the same as your <b>source code</b>. Essentially, this means that the DOM is not a mirror of what you add to a <code>.html</code> document, for example. At times, the DOM may even help correct invalid HTML to aid in the rendering process.</p>

    <p>The DOM is therefore not a webpage; it is an essential step in creating one, however, even though you may never explicitly interact with it.</p>
  </div>
</div>

<br>
