---
title: Media Hosting and Storage
module: topic-07
permalink: /topic-07/media-hosting/
---

<div class="divider-heading"></div>

In the next two sections, we will be looking at the `<img>` `<video>` and `<audio>` elements. With the latter two in particular, you need to be careful when using these elements, as older browsers might not support them and the presentation of the associated media. To create pages viewable by all, you should use a variety of approaches to account for multiple ages of browsers.


## Self-Hosting
**Self-hosting** simply refers to content you've hosted from your site's server. Pages, images, videos, games, you name it. The benefit of this is you have complete control of the site, and can maintain the content yourself. This means you only have to worry about _your_ site failing, not an external source's.

A major con, however, is that web hosting companies often charge extra if you use a lot of bandwidth, and due to the size of most movie files in particular, this can occur easily when self-hosting.

<ul style="list-style-type: none">
  <li class="icon-pro">Ideal for <b>image</b> files.</li>
  <li class="icon-pro">Keeps your content with you, rather than an external server.</li>
  <li class="icon-pro">Provides easy access to content at all times - does not depend on the reliability of another site.</li>
  <li class="icon-con">Not ideal for <b>video</b> or <b>audio</b> files.</li>
  <li class="icon-con">Quickly takes up storage space and can slow down your site and bandwidth.</li>
  <li class="icon-con">Can require extensive markup and additional file formats to make sure the content is available to all visitors.</li>
</ul>


## Third-Party Hosting or Service
**Third-party options and services** provide you affordable solutions to the potential problem of exhausted bandwidth. It is often preferable and encouraged for you to host your media - particularly audio and video - on sites such as ,<a href="https://youtube.com" target="_new">YouTube</a>, <a href="https://vimeo.com" target="_new">Vimeo</a>,  <a href="https://soundcloud.com/" target="_new">SoundCloud</a>, or <a href="https://bandcamp.com/" target="_new">Bandcamp</a>.

<ul style="list-style-type: none">
  <li class="icon-pro">Ideal for <b>video</b> and <b>audio</b> files.</li>
  <li class="icon-pro">Can host large, high-quality versions of files.</li>
  <li class="icon-pro">Will handle compatibility, encoding, and the other details necessary for the media to play on a variety of browsers, without any work from you.</li>
  <li class="icon-con">Not ideal for <b>image</b> files.</li>
  <li class="icon-con">Any unlicenced materials used without permission can be crawled and reported.</li>
  <li class="icon-con">Can become costly to upgrade storage and/or services.</li>
</ul>


<div class="divider-pg"></div>


## Hosting Arguments

There are several things to consider when deciding to host your media on your own site or through a third-party:


### Affordability
As discussed on the previous pages, hosting your own media can take up bandwidth. Increasing bandwidth with service providers and hosting companies usually comes at a hefty price.


### Converting Files
Third-party hosting converts files for you, and increases the compatibility of the media across browsers. This is not to say that you can't provide your own alternative media and conversions, but it can take time. As stated, **always test your site across as many browsers and devices as possible to ensure the page is rendering as intended.**

In terms of downloading files from other sources, you likely will not have access to the original file. For example, with audio, to export an .ogg file (whether it's a song you own or have recently sourced), you may need to use an online converter like <a href="https://convertio.co/mp3-ogg/" target="_new">Convertio</a> or <a href="http://www.zamzar.com/convert/mp3-to-ogg/" target="_new">Zamzar</a>. Again, this is only a band-aide; ideally, you're providing your own created audio (music, recordings, sound effects, etc) which you can export as an .ogg legally.

A similar process is needed to create .webm video files. Certain plugins can be downloaded for video editors like Adobe Premiere so that you can export .webm files without a band-aide conversion.


### Content Protection
You saw how easy it is to download files from `<video>` and `<audio>` elements on the previous page.

If content protection is important, you should use a third party service, such as <a href="https://bandcamp.com/" target="_new">Bandcamp</a>. These services have a vested interest in protecting the content on their servers.

The use of these services may also increase browser compatibility, as they want to ensure their content is available to everyone. This means you don't have to worry about browser compatibility issues as much!


### Exclusion Rules
If the content needs to be exclusive to your site, and not available through a third-party site such as YouTube, then you must host the file. You will need to research current best-practices for self-hosting protected content.


### Final Decision
You will need to be aware of all of these options and potential problems and weight all of the requirements of your project to determine the most appropriate route.
