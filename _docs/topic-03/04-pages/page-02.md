---
title: Page URLs
module: topic-03
permalink: /topic-03/page-urls/
categories: development
tags: directory, organize, page, root
---

<div class="divider-heading"></div>

There are several ways we can control how our `HTML` where our files are stored, retrieved by browsers, and how they appear in the address bar of those browsers.

Consider the file “**about.html**,” found on your website:

<img src="../img/about-page.png" alt="simple about page" style="width: 200px;" />

We need to decide where to place this file in our directory and how the site should locate it. The location of the file will also affect its URL.


## Pages In and Outside Directories:
Browsers treat pages differently from other files. They have _expectations_ of what pages will be titled, what languages they'll use, and where they'll live in the site directory.

Browsers have some default behaviors they do automatically with pages when a visitor accesses the site. Where we put pages is a conscious decision on our part, mostly regarding keeping the site files organized and URLs clean. If you'll remember, anything inside a directory needs that directory added to its **path** to be accessed; too few or too many directories can clutter your site and its pages' URLs.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── page-01.html
└── <i class="far fa-folder-open"></i> directory-name/
    └── page-02.html
</pre>




<div class="divider-heading"></div>

<p style="font-size: 1.2em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">https://www.baseurl.com/about.html</span>
</p>


One way to avoid long URLs is to place the page in the root of the site (in our case, **MART361-WebDesign/**). No additional pathing is needed, as the page is not in any other directories.

We can still have additional pages that we explicitly address. For example, we could have other HTML pages at the same directory level, such as a `contact.html`.

This method is sufficient for sites with few pages. But for sites with many, using child directories is preferable, as it helps with site organization.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── about.html <i class="fas fa-long-arrow-alt-left bounce-x-left"></i>
├── index.html
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css
└── <i class="far fa-folder-open"></i> images/
    ├── <i class="far fa-image"></i> photo-1.jpg
    └── <i class="far fa-image"></i> photo-2.jpg
</pre>



<div class="divider-heading"></div>

<p style="font-size: 1.2em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">https://www.baseurl.com/about/</span>
</p>


If you wished to have a "cleaner" looking URL, you could create an additional child directory labeled `about/` and place a file saved as `index.html` within that directory.

You'll see how an `index.html` is one of those files browsers expect to find in the next sub-topic. Because of this, if an `index.html` file is in a directory, you usually do not have to include it in the file path; the browser will request it automatically.

<span class="label label-info">Note</span> Notice how we do not add `/index.html` at the end of the URL above; instead the URL simply ends with a directory slash (**/**).


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
├── <i class="far fa-folder-open"></i> about/
│   └── <i class="fab fa-html5"></i> index.html <i class="fas fa-long-arrow-alt-left bounce-x-left"></i>
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css
└── <i class="far fa-folder-open"></i> images/
    ├── <i class="far fa-image"></i> photo-1.jpg
    └── <i class="far fa-image"></i> photo-2.jpg

</pre>





<div class="divider-heading"></div>

<p style="font-size: 1.2em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">https://www.baseurl.com/pages/about.html</span>
</p>


For our class, we will create some of our **assignment/** and **project/** directories with a sub-directory called **pages/**. It will contain all of our additional `.html` pages, not <u>any</u> of which will be called `index.html`.

This structure is suitable for learning directory structure for the first time, but because these sub-directories will not have an `index.html` file to request, `https://www.baseurl.com/pages/` will likely return a 404 error.


<div id="code-heading">Directory Tree</div>
<pre id="bash">
.
├── index.html
├── <i class="far fa-folder-open"></i> css/
│   └── <i class="fab fa-css3-alt"></i> style.css
├── <i class="far fa-folder-open"></i> images/
│   ├── <i class="far fa-image"></i> photo-1.jpg
│   └── <i class="far fa-image"></i> photo-2.jpg
└── <i class="far fa-folder-open"></i> pages/
    ├── <i class="fab fa-html5"></i> about.html <i class="fas fa-long-arrow-alt-left bounce-x-left"></i>
    ├── <i class="fab fa-html5"></i> contact.html
    └── <i class="fab fa-html5"></i> gallery.html
</pre>


<span class= "label label-success">Neat-O</span> This site has over 100 child and grandchild directories to keep its many pages organized!
