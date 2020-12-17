---
title: Navigating to Sections on the Same Page
module: topic-08
permalink: /topic-08/basic-nav-section/
---

<div class="divider-heading"></div>

When pages are long, or visitors are expected to interested in specific topics, you can section the page using `<div>`s with unique `id`s. A page can then include its own navigation with links to those unique sections.

<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="mdEJVJG" data-default-tab="html,result" data-user="retrog4m3r" data-pen-title="HTML Nav Element, Page Navigation" class="codepen"></p>
</div>


<span class="label label-info">Note</span> It is considered good practice to include “back to top” options for the user, to avoid excessive scrolling and confusion. This can be done by using `#` as the [source's placeholder](https://www.w3.org/TR/html5/browsers.html#dom-location-hash), or creating an `id` at the page's beginning.
