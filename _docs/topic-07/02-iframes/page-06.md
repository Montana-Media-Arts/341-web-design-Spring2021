---
title: Websites in the iframe Element
module: topic-07
permalink: /topic-07/iframe-element-websites/
---

<div class="divider-heading"></div>

Some websites allow their pages to be loaded on other sites using iframes.

Depending on the size of the iframe, you may see different layouts for versions of the site. For example, in the NASA site below you should see a “mobile view” or “compressed view” optimized for smaller portals (in this case, for windows less than ~1025px.)


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<iframe src="https://solarsystem.nasa.gov/planets/dwarf-planets/pluto/overview/" width="600px" height="500px"></iframe>
```


<div style="width: 600px; height: 500px; margin: auto">
  <iframe src="https://solarsystem.nasa.gov/planets/dwarf-planets/pluto/overview/" width="100%" height="500px"></iframe>
  <p><a href="https://solarsystem.nasa.gov/planets/dwarf-planets/pluto/overview/" target="_blank"><cite>NASA Science: Solor System Exploration - the Dwarf Planet Pluto</cite></a></p>
</div>


<br><br>


<div class="divider-pg"></div>


## How-To:
To embed an external site to your page, simply build the `<iframe>` element, and include the site's absolute URL.

<span class="label label-danger">Important</span> For a variety of reasons, not all sites will work in an iframe. Including a hyperlink to the site below the iframe is a good idea. You can test a site using an <a href="http://www.tinywebgallery.com/blog/advanced-iframe/free-iframe-checker" target="_blank">iframe checker</a>.
