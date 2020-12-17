---
title: Styling with Classes
module: topic-07
permalink: /topic-07/html-classes/
---

<div class="divider-heading"></div>

In addition to the id attribute, the **class attribute** is another attribute that is valid in every HTML element.

<div class="container-row">
  <img src="../img/legos-classes.png" alt="stacked building blocks with similar class names" title="Similar blocks can have the same class!" style="float: right; width:300px; margin-top: 0; " />

  <p>Like the id attribute, the class attribute is an identifier and selector value for HTML elements. The class attribute groups <b>similar</b> types of elements together by using the same name value. This allows for easy styling of these elements with same CSS code.</p>
</div>


<div class="divider-pg"></div>


## Naming Practices for Classes
The class attribute follows the same technical naming conventions as the id attribute. As with the id attribute, the class attribute value should be as descriptive as possible about the function or element types groups, while prioritizing both brevity and readability.

<span class="label label-info">Note</span> Unlike the id attribute which should contain a single unique id value, elements may have <u>more than one class</u> assignment. In this case, spaces separate the class names.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<div id="example-1" class="class-name-1 class-name-2 notice-the-space">
    <p>Notice the space between each of the three class names.</p>
</div>

<div id="example-2" class="class-name-2">
    <p>This paragraph has a unique id, but the same "class-name-2" as the one above it.</p>
</div>
```
