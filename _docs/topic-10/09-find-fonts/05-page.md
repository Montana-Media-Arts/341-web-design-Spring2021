---
title: Other Properties
module: topic-10
permalink: /topic-10/font-face-other/
---

<div class="divider-heading"></div>

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;">
      <span style="color: #999;">@font-face {</span><br/>
        <span style="color: #999;margin-left: 40px;">font-family: '...';</span><br/>
        <span style="color: #999;margin-left: 40px;">src: url('#') format('...');</span><br/>
        <span style="color: #79AF33; font-weight: bold; margin-left: 40px;">font-weight: ;</span><br/>
        <span style="color: #79AF33; font-weight: bold; margin-left: 40px;">font-style: ;<br/></span>
      <span style="color: #999;">}</span>
    </p>
  </div>
</div>

If you intend to make more than one version of a font available, such as bold or true italic, you will **have to** also include these font packages and tell the browser as much.

When importing a font with `@font-face`, there are two additional properties that can be set, `font-weight: ` and `font-style: `. Setting these during font import makes them available to the browser.

To use the font, then simply specify the weight and/or style in the CSS element rule, matching what you specified during font import.
