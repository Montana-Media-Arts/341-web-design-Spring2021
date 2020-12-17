---
title: Font Variant
module: topic-10
permalink: /topic-10/font-variant/
---

<div class="divider-heading"></div>

There are two properties that allow developers to set the capitalization of text. The first is **font-variant**. This property allows developers to specify whether text should appear in all caps, with 'non-capitalized' letters being displayed as small caps.

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
* {
  font-variant: normal;
}
```

`font-variant: ` accepts these term values:

- `normal` (default)
- `small-caps` (display small-caps font)


In a small-caps font, all lowercase letters are converted to uppercase letters. However, the converted uppercase letters appears in a smaller font size than the original uppercase letters in the text.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="MWeJZYb" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Font-Variant (Toggle)" class="codepen"></p>
</div>

<!--<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="zPYBow" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-08] Caps & Cases, Pt. 1" class="codepen"></p>
</div>-->
