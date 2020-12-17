---
title: Float in Practice
module: topic-11
permalink: /topic-11/float-example/
---

<div class="divider-heading"></div>

In the following example, the same block of html is presented twice. In the first version, floats are used to place two red blocks on the left side, and one on the right side. A heading and paragraph text then "flow" around them.

In the second block, no floats are used, to present a comparison of what "normal flow" would like.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="WNxJepd" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Float, Pt. 1" class="codepen"></p>
</div>

#### With `clear:`

In the below example, the same code from the above "Example 1" was taken. However, a `clear: left;` was added to the paragraph element. Notice that this forces it to a new line, below the red squares, whereas, before it started between the two squares.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="qBNYWmW" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Float, Pt. 2" class="codepen"></p>
</div>
