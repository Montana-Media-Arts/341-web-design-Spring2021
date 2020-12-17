---
title: E-mail Links
module: topic-05
permalink: /topic-05/email-links/
categories: html
tags: elements, email, link
---

<div class="divider-heading"></div>

A widespread type of hyperlinking is to create an **email link** within a page. Creating an email link requires prepending the “`mailto:`” to the desired email address.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<a href="mailto:user@example.com">User's E-mail</a>
```


So, to create a hyperlink that e-mails me:


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="JjXmbwb" data-default-tab="html,result" data-user="michaelcassens" data-embed-version="2" data-pen-title="[Intro-Web-Dev] Topic-05: Links Pt. 4" class="codepen"></p>
</div>


<span class="label label-info">Note</span> Clicking on such a link in a webpage will cause the webpage to try and open the user's default email application. For that reason, it is also good practice to write the full email address out. That way, a user can easily copy the browser's address into the email client of their choice.
