---
title: The Meta Element
module: topic-07
permalink: /topic-07/meta-about/
---

<div class="divider-heading"></div>

If you remember from a few Topics back, we explored how **meta elements** are placed inside of the `<head>` element, and briefly described what role they perform. Let's dig a little deeper into this concept.

<p><span class="remember-text">Remember?</span><br/>
The <code>&lt;meta&gt;</code> element <a href="../../topic-05/head-meta/" target="_new">describes metadata about an HTML page</a>. This <b>metadata is not displayed to users</b>, but used by browsers and search engines. This may describe  what character encoding the document contains, the published date, author information, descriptions for search engines, keywords, etc.</p>


The meta element is an “empty element.” As such, no closing tag is necessary. Also, as with form elements, metadata is always passed as a name="value" pair. Typically via the `name=""` and `content=""` attributes.

<span class="label label-danger">Important</span> `<meta>` elements are _always_ placed inside the `<head>` element.



<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Meta data and information about your site, not visible to visitors. -->
  </head>

</html>
```
