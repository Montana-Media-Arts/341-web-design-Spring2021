---
title: Word Spacing
module: topic-10
permalink: /topic-10/word-spacing/
---

<div class="divider-heading"></div>

In addition to being able to adjust the space between characters, developers can adjust the amount of space between words only, using the `word-spacing: ` property.

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
* {
  word-spacing: normal;
}
```

`word-spacing:` accepts these term values:
- `normal` (default, 0.25em)
- pixels (`px`)
- points (`pt`)
- percent (`%`)
- ems (`em)`
- ...most other size terms, including negative values


### “Why adjust word spacing?”

Like with `letter-spacing: `, changing the distance between words and shift the visual message of the text as part of branding or design work. Fonts are are wider can generally see a decrease in `word-spacing: ` without sacrificing too much legibility, although this should be a thoughtful decision.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="NWrdemp" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Word-Spacing" class="codepen"></p>
</div>
