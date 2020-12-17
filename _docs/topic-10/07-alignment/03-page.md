---
title: Indentation
module: topic-10
permalink: /topic-10/text-indent/
---

<div class="divider-heading"></div>

**First-line indents** are another typesetting property that CSS allows for the manipulation of. This property is controlled via `text-indent: `.

This property controls how much the first line of a paragraph is indented.

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
* {
  text-indent: 0;
}
```

As with many text properties, this once can be passed absolute values with pixels (`px`) or points (`pt`). It can also be passed relative values, such as `em`s.

`text-indent:` accepts these term values:
- `normal` (default, no extra spacing, 0)
- pixels (`px`)
- points (`pt`)
- percent (`%`)
- ems (`em)`
- ...most other size terms, including negative values

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="mdERvMO" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Text Indent" class="codepen"></p>
</div>
