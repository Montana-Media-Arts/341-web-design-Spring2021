---
title: Images
module: topic-04
permalink: /topic-04/one-tag-images/
categories: html
tags: empty, image
---

<div class="divider-heading"></div>

We will get into images much later in the course, but you can already add images to your new HTML files by using a little borrowed code. Like the others in this section, the image tag, `<img />`, creates an empty element. `src=""` tells the browser the location of the image or the URL to the file.

Please note that instead of wrapping the URL in parentheses (`(...)`) as we do in Markdown, in HTML, we use quotations (`"..."`) to contain the URL to the file.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<img src="./images/name-of-image.jpg" />
```


Compare this to Markdown:


<div class="code-heading">
  <span class="md">Markdown</span>
</div>
```markdown
![My Image](./images/name-of-image.jpg)
```


At this stage in your development journey, you can get an image to embed very similarly as you would in Markdown using the element `<img src="..." />`.


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="MQbOdj" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Image Element Src Attribute" class="codepen"></p>
</div>
