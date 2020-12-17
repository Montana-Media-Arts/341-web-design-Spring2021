---
title: Meta
module: topic-05
permalink: /topic-05/head-meta/
categories: html
tags: author, charset, description, elements, head, meta
---

<div class="divider-heading"></div>

The **META element** lives inside the head element and contains information about that webpage.
It is not visible to users but fulfills many purposes, such as telling search engines about your page, who created it, and whether it is time-sensitive.

The meta element is an _empty element_, like the upcoming link element. The most common attributes are 'name' and 'content'. These attributes are often used together and specify the properties of the entire page:

1. The value of the name attribute is the property you are setting.
2. The value of the content attribute is the value that you want to give to this property.

For example, on the second meta line below, the name attribute indicates an intention to specify a page's description. The content attribute is where this description is defined.
The value of the name attribute can be anything you want it to be.

We will look at the Meta element more later. For the time being, however, you should include the following meta elements in your pages:

- _charset_ - This defines the character set to use for page display. A web browser must know which character set (character encoding) to display an HTML page correctly. **UTF-8** (Unicode) covers almost all of the characters and symbols in the world. This character set includes the original ASCII standard that covers most of the character symbols you use.
- _Description_ - This contains a description of the page, which is commonly used by search engines to understand its meaning. As such, it should be less than 155 characters.
- _Author_ - This defines the author of the webpage.

<span class="label label-info">Note</span> The _charset_ attribute is usually the first element in the head.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>
<html>
  <head>

    <!-- Define the character set used: -->
    <meta charset="UTF-8">

    <!-- Provide a description of your page: -->
    <meta name="description" content="A short description...">

    <!-- Provide the author information for the page: -->
    <meta name="author" content="Your Name">

  </head>

</html>
```
