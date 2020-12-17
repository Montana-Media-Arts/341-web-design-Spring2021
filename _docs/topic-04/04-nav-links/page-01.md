---
title: Internal Linking
module: topic-04
permalink: /topic-04/nav-links/
categories: development
tags: directory, link, relative, repository, url
---

<div class="divider-heading"></div>

## Relative Linking Within Your Repository
As you now know, the internet is built foundationally on links and inter-connected files and systems. We'll get into **hypertext** and **hyperlinks** later on in the course, but for right now, let's continue the <a href="https://montana-media-arts.github.io/341-web-design-Fall2020/topic-02/urls-absolute/" target="_new">discussion on absolute URLs</a> and <a href="https://montana-media-arts.github.io/341-web-design-Fall2020/topic-02/urls-relative/" target="_new">discussion on relative URLs</a>, looking at linking the files within our directory together.

You've done some linking in **markdown** already, using outside sources and _absolute_ URLs:


<div id="code-heading">Markdown</div>
```markdown
[discussion on absolute URLs](https://montana-media-arts.github.io/341-web-design-Fall2020/topic-02/urls-absolute/)
```


<br />

But I can also link to pages on this website using _relative_ URLs, as long as I stay within my  `/MART341-WebDesign` repository. As the administrator of this site, I can link to the same page like so:


<div id="code-heading">Markdown</div>
```markdown
[discussion on relative URLs](/topic-02/urls-relative/)
```


<br />

Within our _MART341-WebDesign_ repo, I can use either of these methods to link back to the same page. One is much more efficient for me to type and doesn't require anything to be sent to GitHub's servers yet.
