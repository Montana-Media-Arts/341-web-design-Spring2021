---
title: Web Directories (“Folders”)
module: topic-01
permalink: /topic-01/directories-web/
categories: development
tags: directory, file, folder, organize, path
---

<div class="divider-heading"></div>


We organize these different files into groups, just like you do with your other non-web-based files. We commonly refer to the containers of these files as "folders" because that's how they function. Most operating systems represent these folders with graphic icons (folders) to make visual associations.

<div style="padding: 20px 0px 80px 0px;">
  <p align="center">
    <img src="https://www.nba.com/nuggets/sites/nuggets/files/dn-primary-website-logo.png" alt="Denver Nugget's Logo" style="border: none;"/>
  </p>
  <p class="url-example">https://www.nba.com/nuggets/sites/nuggets/files/dn-primary-website-logo.png</p>
</div>

The **path** (or “directions”) for this image, `/nuggets/sites/nuggets/files/` actually refers to the nesting of its folders, or **directories**.

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
└── <i class="far fa-folder-open"></i> nuggets/
    └── <i class="far fa-folder-open"></i> sites/
        └── <i class="far fa-folder-open"></i> nuggets/
            └── <i class="far fa-folder-open"></i> files/
                └── <i class="far fa-image"></i> dn-primary-website-logo.png

</pre>


<span class="label label-info">NOTE</span> “Folders” and “directories” refer to the same concept, but “directory” should be used when discussing file systems. You will hear us use directory most often.
