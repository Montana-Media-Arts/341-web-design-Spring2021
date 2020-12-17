---
title: Font Weight
module: topic-10
permalink: /topic-10/font-weight/
---

<div class="divider-heading"></div>

<link rel="stylesheet" href="../ex-files/fonts.css">
<link rel="stylesheet" href="../ex-files/style.css">

Within CSS, **font weight** and the `font-weight` property (in its most basic use) specifies whether a font is "normal" or "bold".

**Bold** is the weight you are familiar with: setting this in CSS should cause the text to look the same as if would if you used the `<b>...</b>` tags in HTML. In addition to the bold font weight, depending on the font-family superclass, it is possible to also specify varying weights thus:

`font-weight:` accepts these term values:
- `lighter`
- `normal`
- `bold`
- `bolder`

`font-weight:` accepts these number values:
- `100`
- `200`
- ... through `900`


<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="yLJgGBa" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Adding Emphasis" class="codepen"></p>
</div>


<span class="label label-info">NOTE:</span> Using anything beyond `bold` or `bolder` will usually require different styles of that font from the server. See the [end of this subtopic](../using-weight-style/) for more.
