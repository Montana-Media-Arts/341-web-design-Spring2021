---
title: Action
module: topic-06
permalink: /topic-06/form-action/
---

<div class="divider-heading"></div>


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width: 50%">
      <span class="sr-only">50% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><form</span> <span style="color: #79AF33; font-weight: bold;">action="#"</span> <span style="color: #999">method="..." id="..." class="..."> ... </form></span></p>
  </div>
</div>


The `action` attribute is a link to a server-side script (i.e. a file on another computer, not the users computer). Typically this file is code file (php, asp.net, python, jsp, etc) on a server that will do 'something' with the user data before returning information back to the browser.  **Note:** we talk about this in MART 461 Web Server Technologies

<span class="label label-info">NOTE:</span> The value of the action attribute will always be an URL.
