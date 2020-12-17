---
title: Adding HTML Comments
module: topic-05
permalink: /topic-05/html-comments/
categories: html
tags: comment
---

<div class="divider-heading"></div>

Comments are designated somewhat different in every language. In HTML, however, they are defined using a **tag**. The browser will ignore anything placed within this tag.

<span class="label label-info">Note</span> Comments are not hidden from _other people_. Comments, if included in your deployment code, will be available for the whole world to see.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!-- This is an HTML comment. -->


<!-- Everything placed between the 'dashes' is part of the comment. -->
<!-- Comments should not span multiple lines in HTML.
        Sometimes this can cause issues for a browser's processor.

        This comment is considered as bad style. -->
<!-- Instead: -->
<!-- You should place each line of a multi-line comment within a comment tag. -->
<!-- That would be considered proper style. -->
```
