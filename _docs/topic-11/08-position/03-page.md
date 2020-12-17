---
title: Relative Position
module: topic-11
permalink: /topic-11/position-relative/
---

<div class="divider-heading"></div>

Setting the position property to "relative" (`position: relative;`) allows developers to specify an amount off of the normal flow position. Rather, when an element is set to relative, it will still follow normal flow, but can be moved, relative to that position.

**NOTE:** This does not effect the position of surrounding elements. These other elements will continue to be positioned where they would in normal flow. This is true even if the altered element is positioned over them.

In the below example, notice how the `top:` and `left:` properties are used to move the second paragraph to the lower-right of where its
normal flow" position would have been.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="PozeYZb" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Position, Pt. 1 " class="codepen"></p>
</div>
