---
title: Adding Attributes
module: topic-05
permalink: /topic-05/attributes/
categories: html
tags: attribute, paragraphs, tags
---

<div class="divider-heading"></div>

**Attributes** provide additional information about an HTML element. Attributes may include languages (US-English vs. French), URL links for text, the size to display a picture, or ways of identifying specific elements.

Place Attributes inside the opening tag for which the element they refer. Attributes always provide a **key= "value"** pair with the **key** as the identifier that the browser processor will recognize. The W3 Consortium defines these keys based on the HTML5 specification. The **value** provides information about the attribute.

Double quotations always surround the value. One reason for this is that it allows for spaces to be used within an attribute's value. Furthermore, the attribute will have one space between the tag label and the attribute, as well as between any subsequent attributes.

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html

<p align="left">This is a paragraph element, made with "<p>" tags.
<br/>
It will align to the left of its container.</p>

```
