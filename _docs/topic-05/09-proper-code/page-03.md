---
title: 2. Properly Nested Tags
module: topic-05
permalink: /topic-05/burrito-tags/
categories: development
tags: code, elements, best-practice
---

<div class="divider-heading"></div>

## The Tag Burrito
We "wrap" elements in opening and closing tags, as you know. You're now familiar with single-tag element sets like `<p>...</p>`, but elements can have multiple tags. It's best practice to layer these sets in concentric orbits around the element.

This basically looks like `<tag3><tag2><tag1>...</tag1></tag2></tag3>`


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>

<html>
  <body>

    <!-- From a recently released deleted scene: -->
    <p>Spengler: "There's something very important I forgot to tell you."</p>
    <p>Venkman:  "What?"</p>
    <p>Spengler: "Dont cross the streams."</p>
    <p>Venkman:  "Why?"</p>
    <p>Spengler: "It would be bad."</p>
    <p>Spengler: "Almost as bad as <u><i>improperly nesting HTML tags.</u>"</p></i>
    <p>Venkman:  "What's proper?"</p>
    <p>Spengler: <u><i>"This."</i></u>.</p>

  </body>
</html>
```


<p class="img-caption"><a href="https://youtu.be/jyaLZHiJJnE" target="_blank">True story</a>.<p>
