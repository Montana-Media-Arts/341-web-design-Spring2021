---
title: Pages
module: topic-01
permalink: /topic-01/web-files-pages/
categories: development
tags: design, file, page
---

<div class="divider-heading"></div>


Web designers use all types of files to create sites including `.html`, `.css`, `.php`, `.aspx`, and more. How one creates and saves files affect how they are processed; a `.css` files do not display the same as an `.html` web page.

Web sites require `.html` (or other web) ** Pages** because they contain the visible content of that site. Furthermore, other files (such as images and other media) typically are accessed by pages using hyperlinks, embeds, and more, which we will cover in greater detail.


<div class="divider-pg"></div>


<div class="row img-text-columns">
  <div class="col-lg-2">
    <img src="../img/web-pages-html.svg" title="HTML" alt="html icon" />
    <span>page.html</span>
  </div>
  <div class="col-lg-10">
    <h3><b>H</b>yper<b>t</b>ext <b>M</b>arkup <b>L</b>anguage (<b>HTML</b> or <b>HTM</b>)</h3>
    <p>HTML is the standard language used to create web pages. HTML provides the structure of the page, using <i>elements</i> to create headings, paragraphs, lists, tables, links, etc. Properly-laid-out HTML is designed to enhance accessibility, and provide structured content outside of decorative styling.</p>

    <ul class="pros-and-cons">
      <li class="icon-pro">Easy-to-learn, free or low-cost.</li>
      <li class="icon-pro">Widely-used; standardardized.</li>
      <li class="icon-pro">Extensive; has a large library and support community.</li>
      <li class="icon-con">Requires a browser to correctly render the markup.</li>
      <li class="icon-con">HTML Lexicon is in American English, and may require extra interpretation for non-English speakers.</li>
    </ul>
  </div>
</div>

<div class="row img-text-columns">
  <div class="col-lg-2">
    <img src="../img/web-pages-css.svg" title="CSS" alt="css icon" />
    <span>page.css</span>
  </div>
  <div class="col-lg-10">
    <h3><b>C</b>ascading <b>S</b>tyle <b>S</b>heet (<b>CSS</b>)</h3>
    <p>CSS is used to control how the page looks and responds to different display types. CSS is used to “decorate” the site. For example, CSS provides layout, color, interactive elements, fonts, and other formatting. HTML provides the contents of the page and CSS specifies how the site will look. Using a stylesheet greatly speeds up development time, as a single sheet can affect all pages in the site.</p>

    <ul class="pros-and-cons">
      <li class="icon-pro">Speed and consistency in styling pages site-wide.</li>
      <li class="icon-pro">Supported by nearly all browsers.</li>
      <li class="icon-pro">Extensive; has a large library and support community.</li>
      <li class="icon-con">CSS is different from HTML, and requires users to learn different syntax.</li>
      <li class="icon-con">Interpreted differently across browsers including mobile; requires testing.</li>
    </ul>
  </div>
</div>

<span class="label label-success">Note</span>If there are separate HTML and CSS page, they must be linked together for the CSS to affect the HTML.  This will be discussed later.
