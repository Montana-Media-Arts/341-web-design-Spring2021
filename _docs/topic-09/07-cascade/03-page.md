---
title: Specificity
module: topic-09
permalink: /topic-09/cascade-specify/
---

<div class="divider-heading"></div>

Rules which are more **specific** will take precedence over less specific rules. This is true even if the less specific rule is defined last.

For example;
- `h1 p {}` is more specific than `p {}` alone.
- `.box-two` is more specific than `<div>`.
- `#first-paragraph-id` is more specific than `.box-two`


<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="NWrNmgM" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="[Topic-07]  Cascading, Pt. 2" class="codepen"></p>
</div>
