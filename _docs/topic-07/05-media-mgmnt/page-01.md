---
title: Media on the Web
module: topic-07
permalink: /topic-07/media-about/
---

<div class="divider-heading"></div>

Nearly every page we visit has some form of embedded media.

The `<img>` tag has been around since the early '90s, and is one of the foundational elements of HTML.

[HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) introduced new features, specifications, and elements, like the  `<video>` and `<audio>` elements. As their names imply these elements are intended to provide multimedia functionality to webpages. One of the stated goals for the W3 Consortium with these new specs was to address multimedia in order to “make video and audio first-class citizens in the Open Web.”

As with all stages in web design, it is important to keep a well-organized media directory. _As HTML5 is still in development and being accepted by browsers, we need to provide text or fallback files should the intended media files or elements not be accessible._


## Directory Structure

As you've been doing with image files, you are encouraged to store media files in a separate sub-directory so as to keep the directory structure of your site clean. Images generally get their own sub-directory.

The following demonstrates a possible directory structure:


<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
├── index.html
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   │   <i class="far fa-image"></i> photo-2.jpg
│   └── <i class="far fa-image"></i> movie-poster.png
└── <i class="far fa-folder-open"></i> media/
    ├── <i class="fas fa-music"></i> song.mp3
    ├── <i class="fas fa-music"></i> song.ogg
    ├── <i class="fas fa-video"></i> movie.mp4
    └── <i class="fas fa-video"></i> movie.webm
</pre>


<span class="label label-info">Note</span> GitHub has a repo limit of **1 GB**, which is pretty small when thinking about website media. The next few pages list some options for finding smaller files to use.
