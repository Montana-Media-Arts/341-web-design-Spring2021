---
title: Relative URLs
module: topic-02
permalink: /topic-02/urls-relative/
categories: development
tags: file, folder, relative, url
---

<div class="divider-heading"></div>

<p style="font-size: 1.2em; font-weight: bold; letter-spacing: 2px; margin: 3rem 0;">
  <i class="fas fa-long-arrow-alt-right" style="color: #DF382C"></i>
  <span style="font-family: monospace;">./images/profile.png</span>
</p>


**Relative URLs** contain no protocols or domain information. This is convenient because they are shorter, but can _only_ reference files in the same path. If I am the owner of **www.example.com** and am embedding "profile.png" on my About page, I can do so relatively with "./images/profile.png" as long as the images folder is in the same path as my page. I do not need an absolute URL.

The "." is a path component stating that we need to remain in the current level of our directory hierarchy. Effectively, it says _"to find this file, begin here and then head down inside the images folder, where you'll find profile.png."_

To continue our analogy, since I'm already inside the same building as "profile.png," I only need its apartment name to find it.

This will be handy for you as you start to link to your own images within your repo.

<img src="../img/url-building.gif" alt="apartment building" style="width: 400px;" />
<div class="img-caption">If I'm on the same floor as “images,” I simply have to enter that apartment to find profile.png.</div>
