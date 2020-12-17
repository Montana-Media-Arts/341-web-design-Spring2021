---
title: Building a Page (Step-by-Step)
module: topic-07
permalink: /topic-07/grouping-elements/
---

<div class="divider-heading"></div>

When thinking about page structure and layout, a good plan is to start with **divs** and begin identifying and grouping elements within:

1. “How many _divisions_ (or sections) of my page do I want?” Create these `<div></div>` elements accordingly.
2. Name important divs using the `id=""` attribute.
3. Within the divs, add [structural html](../../topic-04/structural-markup/) content, like [headings](../../topic-03/using-headings/), [paragraphs](../../topic-03/paragraphs), etc.
4. Add `class=""` attributes to divs that need styling.
5. Use the `<span></span>` element around structural elements that need inline styling, like specific words of a paragraph.
6. Within the divs, add illustrative elements like [images](../img-element-review), [audio](../audio-element-review), or [video](../video-element-review).
7. Repeat.


<div class="divider-pg"></div>


## Step-By-Step
Below is a page with two descriptions of popular sports. Here are the steps taken to create this page:

1. Created 3 empty **divs**, `<div>...</div>`
2. Added **ids** to those divs, to make them unique:
  - `id="header"`
  - `id="football-block"`
  - `id="esports-block"`
3. Added structural **content** to both divs, including headings and paragraphs.
4. Applied the **classes** listed in the `<head>`:
  - `class="page-block"` to _all_ the divs, as they should visually appear the same (color, font-size, etc).
  - Added the `centered` class to all content to be centered on the page.<br/>
  <span class="label label-info">Note</span> To apply multiple classes to a div, simply add a “space” between classes. For example `<div class="page-block centered">`
5. Added a **span** to the first sentence of each paragraph, with the class `class="first-line"`. With the applied styling stated in the `<head>`, each sentence with this span will be italic.
6. Added the illustrative content - the 2 flag images.
7. Swelled with pride.


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="BaKXvqd" data-default-tab="html,result" data-user="retrog4m3r" data-pen-title="HTML Block-Level and Inline Elements" class="codepen"></p>
</div>
