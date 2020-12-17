---
title: Links to Other Sites
module: topic-05
permalink: /topic-05/links-to-others/
categories: html
tags: absolute, elements, link, url
---

<div class="divider-heading"></div>

Links that include the “<code>http/https</code>” as part of the entire URL are known as <b>absolute URLs</b>.</p>

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<a href="https://example.com" target="_blank">Link to Example.com</a>
```


Notice in the above link that it includes “`https`”. The “`https`” is required to signify to the browser that this is an ‘external’ link outside the current document’s directory/server. **You must include either “`http`” or “`https`”.**

The former is an older, established, version of the “hypertext transfer protocol”, which specifies data transfer between clients. The latter is a “secure” version of this protocol. Whenever possible, you should provide “`https`” links (check that they work first), as it allows for a safer browsing experience.


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="Rwaeoqx" data-default-tab="html,result" data-user="michaelcassens" data-pen-title="External HTML Links" class="codepen"></p>
</div>
