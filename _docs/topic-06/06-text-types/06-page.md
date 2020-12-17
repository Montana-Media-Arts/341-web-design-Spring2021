---
title: Columns and Rows
module: topic-06
permalink: /topic-06/text-cols-rows/
---

<div class="divider-heading"></div>

In a textarea, one can specify the number of columns and rows, but using the following attributes `cols` and `rows`. These attributes change the size of the displayed element, as well as how text looks when typed.

- `cols` is the width of the textarea in character widths (i.e. this is the number of characters that will fit from left to right).
- `rows` is the number of visible lines.


<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
<p>
  Comments or Concerns:
  <textarea name="comments" id="test-textarea" cols="20" rows="4">Enter up to 500 characters...</textarea>
</p>
```

<div class="row" style="margin-top: -30px;">
  <div class="col-lg-12">
    <div class="bs-component">
      <div class="panel panel-success">
        <div class="panel-heading">
          <h4 style="text-transform: uppercase; margin: inherit;">
            <i class="fa fa-check-circle" aria-hidden="true" style="margin-right: 10px"></i>
            Please Enter:
          </h4>
        </div>
          <div class="panel-body">
            <p style="font-size: large;">
              <span style="margin-right: 1em;">Birth Year:</span>
              <input type="text" name="name" id="test-date" maxlength="4" />
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 2.6em;">Net ID:</span>
              <input type="text" name="name" id="test-text" />
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 1.2em;">Password:</span>
              <input type="password" name="password" id="test-password" maxlength="15"/>
            </p>
            <p style="font-size: large;">
              <span>Comments or Concerns:</span>
              <textarea name="comments" id="test-textarea" cols="20" rows="4" style="width:100%; border-color: #D8D8D8 !important; color: #777; font-size: medium">Enter up to 500 characters...</textarea>
            </p>
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> These attributes can also be overridden in CSS.
