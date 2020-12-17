---
title: 3. Width and Height
module: topic-07
permalink: /topic-07/iframe-size/
---

<div class="divider-heading"></div>


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><iframe src="#"</span> <span style="color: #79AF33; font-weight: bold;">width="..." height="..."</span><span style="color: #999">>...</iframe></span></p>
  </div>
</div>


As with the image element, you should always specify the amount of space the `<iframe>` element is suppose to take up on a page. This allows the browser to reserve the appropriate amount of space for the element, even if it takes longer to load than the rest of the page. These attributes are also important when pulling in external websites, as they may be built to use the whole page themselves.
