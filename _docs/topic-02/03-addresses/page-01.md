---
title: Web Addresses
module: topic-02
permalink: /topic-02/urls-addresses/
categories: development
tags: file, folder, path, url
---

<div class="divider-heading"></div>


Generally, we can think about "finding" a web location in two ways: via its _relative_ or _absolute_ address (or **URL**).


## What U. R. L(ooking for)
You invite an old friend to visit you, but they don't know where you currently live. When they ask for your address, you give them your country, state, city, street, and house number.

We find sites and files on the web in the same way, but instead of looking for houses, we're looking for other computers, servers, files, or even queries on a network. A "web address" or **uniform resource locator** (URL) is assigned to every website so that users and servers can find that site quickly and easily.

Directions for a site or file can be broken down similarly (in the most basic sense) to directions to a house, but more applicably into _protocol, domain, path_, and _file_.

Continue to the next page to find out how the web does this.

<img src="../img/url-city.gif" alt="car driving to a city, with map tags floating above the buildings" />
<div class="img-caption">
  You've “invited” someone to view your file. You need to tell them which one, and where to find it.
</div>


<div class="divider-pg"></div>


## Anatomy of a URL
<div class="row img-text-columns">
  <div class="col-lg-3">
    <img src="../img/url-protocol.png" alt="street signs with request and response pointers" title="Protocol" />
  </div>
  <div class="col-lg-9">
    <p>The <b>protocol</b> states how the web browser will communicate with a web server (where your files live on the big, bad web). A common protocol is <i>HTTP</i>, or <i>Hypertext Transfer Protocol</i>.</p>

    <p>In our analogy, think of the protocol like the “country” of your site's address.</p>
  </div>
</div>

<br>

<div class="row img-text-columns">
  <div class="col-lg-3">
    <img src="../img/url-domain.png" alt="billboard with the words www.example.com on it" title="Domain" />
  </div>
  <div class="col-lg-9">
    <p>You have purchased a <b>domain</b> for your site: <i>example.com</i>. You may choose to use a common <b>subdomain</b>, <i>www</i>. Altogether, your site's URL is “<a href="https://www.example.com" target="_blank">http://www.example.com</a>”. Domains are unique; if you own <i>example.com</i>, no one else can. It is the main direction to your site and all its content.</p>

    <p>In our analogy, think of subdomains and domains like the “state,” “city,” “province,” etc, of your site's address.</p>
  </div>
</div>

<br>

<div class="row img-text-columns">
  <div class="col-lg-3">
    <img src="../img/url-path.png" alt="graphic of a person smiling" title="File" />
  </div>
  <div class="col-lg-9">
    <p><b>Paths</b> are instructions on how to navigate directories. They contain all parent and subdirectories (folders inside folders) found en-route to a destination.</p>

    <p>In our analogy, think of the path as step-by-step directions to the final room, which contains a file or page.</p>
  </div>
</div>

<br>

<div class="row img-text-columns">
  <div class="col-lg-3">
    <img src="../img/url-file.png" alt="graphic of a person smiling" title="File" />
  </div>
  <div class="col-lg-9">
    <p>The end of a path often leads to a <b>file</b>, <b>page</b>, or even <b>query</b>. There may be lots of files on your website, like the image <i>profile.png</i> for example, found on your “About Me” page. Where this image lives in your directory structure will dictate how other content is able to locate it.</p>

    <p>In our analogy, think of these path-enders as the residents living at your site's address.</p>
  </div>
</div>


<div class="divider-pg"></div>


<h2 id="dir">Directory</h2>
If the root (`.`) is for `example.com`, your directory for that site might look something like this:

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
├── <i class="far fa-folder-open"></i> content/
│   └── <i class="far fa-folder-open"></i> images/
│       └── <i class="far fa-image"></i> profile.png
├── <i class="fab fa-html5"></i> about.html
└── <i class="fab fa-html5"></i> index.html
</pre>
