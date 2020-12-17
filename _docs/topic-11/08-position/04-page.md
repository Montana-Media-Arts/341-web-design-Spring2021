---
title: Absolute Position
module: topic-11
permalink: /topic-11/position-absolute/
---

<div class="divider-heading"></div>

Setting the position property to 'absolute' (`position: absolute;`) allows developers to specify exactly where on a page an element should be located. This can be accomplished using the position properties mentioned above.

Setting an elements position to 'absolute' also has the effect of taking it "out" of the normal flow. This means other elements will not reserve space for this element.

In the following example, the second paragraph is placed 20 pixels from the top and 100 pixels from the left, regardless of what the other elements are doing or where they are positioned. As a result, this paragraph (`.absolute-element`) is positioned "on top" of the other elements.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="LYZmPGw" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Position, Pt. 2" class="codepen"></p>
</div>
