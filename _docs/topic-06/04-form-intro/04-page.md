---
title: Method
module: topic-06
permalink: /topic-06/form-method/
---

<div class="divider-heading"></div>


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">
      <span class="sr-only">75% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><form action="#"</span> <span style="color: #79AF33; font-weight: bold;">method="..."</span> <span style="color: #999">id="..." class="..."> ... </form></span></p>
  </div>
</div>


Forms can be sent using one of two methods; '`GET`' or '`POST`'.

With the '`GET`' method, values are added to the end of the specified action URL.

This method can be used in searches, or for _retrieving_ data from a server, but keep in mind, it is in clear text in the querystring and is NOT secure.

With the '`POST`' method, values are sent in what are known as 'HTTP headers'. As a rule of thumb, use the '`POST`' method when;

- users are uploading a file.
- the data will be very long
- the data is sensitive (ie. contains passwords)
- The data is intended to alter or access a database on the server.