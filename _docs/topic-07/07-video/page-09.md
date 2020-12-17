---
title: Formats and Browser Support
module: topic-07
permalink: /topic-07/video-formats/
---

<div class="divider-heading"></div>

As with many HTML5 elements including the `<video>` and `<audio>` elements, not all browsers support the same format. Therefore, even with HTML5 you need to provide your files in multiple formats.

## Video Formats
Required self-hosted video formats:

- H.264 (likely MP4): IE and Safari
- WebM or OGG Video: Android, Chrome, Firefox, Opera

We use the `<source>` element inside the multi-source `<video>` element to specify the video source. **This would be used in-place of the `src=""` attribute in the single-source video element.**


## “Not Supported!”
You should include a paragraph element “fallback” that will be displayed if the browser does not support the video element _or_ the format of video used. The browser will display whatever is between the opening and closing video tags.

<span class="label label-info">Note</span> Any written content placed between the `<video>` will display should the video not load in the browser. You should always include some descriptive text of the video (just like with images), so users know what element they are missing out on.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<video src="#" poster="#" width="" height="" preload controls>
  <p>A quick description of the movie...</p>
  <p>Sorry, your browser does not support the video tag.</p>
</video>
```
