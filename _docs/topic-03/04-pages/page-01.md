---
title: The Index
module: topic-03
permalink: /topic-03/page-index/
categories: development
tags: directory, index, request, url
---

<div class="divider-heading"></div>


<div class="container-row">
  <img src="../img/logo-html5.svg" alt="HTML5 Logo" title="HTML5" style="float: right; width: 125px; margin-top: 0;" />

  <p>Almost every website you encounter has a master HTML file called the <b>index.</b> <i>There can be multiple index files on a site, but at least one index is the homepage of the site.</i></p>

  <p>You are going to create a lot of files labeled <code>index.html</code>. Similar to READMEs and GitHub, when a URL is passed to a browser that does not specify a file, the browser automatically “looks for” and requests a <code>index.html</code> from the host server.</p>
</div>


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html <i class="fas fa-long-arrow-alt-left bounce-x-left"></i>
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
└── <i class="far fa-folder-open"></i> pages/
    ├── <i class="fab fa-html5"></i> about.html
    ├── <i class="fab fa-html5"></i> contact.html
    └── <i class="fab fa-html5"></i> gallery.html
</pre>


<span class="label label-success">Neat-O</span> Essentially, this means something like `http://baseurl.com` and `http://baseurl.com/index.html` are the same! (This is not true for all websites, but many of them.)
