---
title: 3. The Head Element
module: topic-03
permalink: /topic-03/head-element/
categories: html
tags: document, head, title
---

<div class="divider-heading"></div>


The **head element** is a container for processing information and document metadata. The header includes elements that may link to other files, hold the author information, and pass the page's name to the processor. The `<head>` contains high-level information about the site, and always comes first within the root element.

In many aspects, the contents are not visible to site visitors. Instead, the `<head>` contains information for indexing the site, like search results. Certain elements in the `<head>` can also dictate how the page will visibly look. In this sense, we can consider the `<head>` to contain the page's thoughts.

The **title element** lives within the head and states the title of the page. The title is the wording that appears on the browser tab for that page.

<span class="label label-danger">Important</span> The `<title>` tag is the only **required** element within the `<head>`, and aptly contains your site's or page's title.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Way-Cool Awesome Site</title>
    <!-- Meta data and information about your site, not visible to visitors. -->
  </head>

</html>
```

