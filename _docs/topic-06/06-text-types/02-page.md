---
title: Plain Text
module: topic-06
permalink: /topic-06/text-plain/
---

<div class="divider-heading"></div>

This following code demonstrates how to create an input element of `type="text"`. Please notice the use of the `<p>...</p>` element to display information text in front of the text box.


<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
<p>
  Net ID:
  <input type="text" name="name" id="test-text" />
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
              <input type="text" name="name" id="test-date" />
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 2.6em;">Net ID:</span>
              <input type="text" name="name" id="test-text" />
            </p>
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> Technically, you can omit the "type" from the input element if you want a text box. However, best practices suggest that one is explicit in their code to prevent errors.
