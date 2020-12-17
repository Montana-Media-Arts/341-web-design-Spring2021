---
title: Page-to-Page Navigation
module: topic-04
permalink: /topic-04/nav-pages/
categories: html
tags: elements, link, navigation
---

<div class="divider-heading"></div>

One of the Internet's primary functions was to easily reference research when citing others, with an ability to directly "link" to their work.


## Hyperlink
In computing, a **hyperlink**, or merely a link, refers to data that the reader can directly follow either by clicking, tapping, or hovering. A hyperlink points to a whole document or a specific element within a document.


## Hypertext
**Hypertext** is text with hyperlinks. The text that is linked is called _anchor text_. A software system used for viewing and creating Hypertext is a hypertext system, and to create a hyperlink is to hyperlink (or to link). A user following hyperlinks is said to navigate or browse the Hypertext. [<sup>\[1]</sup>](https://en.wikipedia.org/wiki/Hyperlink "Wikipedia - Hyperlink")

<span class= "label label-info">Note</span> Link text should be specific about where the user will be going if they click a link. Link text **should not** be simple text such as "Click Me!" Instead, the correct style would dictate that the link text be a description of the site, name, or information that informs the user.

<ul style="list-style-type: none">
  <li class="icon-con">“Want to learn more? <a href="#" style="color: blue; text-decoration: underline">Click here</a>!”</li>
  <li class="icon-pro">“See <a href="#" style="color: blue; text-decoration: underline">this page about hyperlinks</a> to learn more.”</li>
</ul>


<div class="divider-heading"></div>

With **links** being such a basic and historical part of the Internet, they also have a straightforward tag; `<a>...</a>`. Any text between a hyperlink element's tags will display as "hypertext". Traditionally, this has been blue, underlined text, visually signifying to the user that <a href="#" style="color: blue; text-decoration: underline">the text is a link</a>.

The author must include a **hyper reference** attribute within the opening tag to link to another document. This attribute is signified with `href=""`.

<span class="label label-info">Note</span> `#` is a URL placeholder.


<div id="code-heading">HTML</div>
```html
<a href="#">link text</a>
`"


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="aLWJpd" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Links (No Target)" class="codepen"></p>
</div>
