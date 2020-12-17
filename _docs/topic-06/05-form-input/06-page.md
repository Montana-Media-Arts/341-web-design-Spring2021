---
title: The &lt;input&gt; Element
module: topic-06
permalink: /topic-06/input-element/
---

<div class="divider-heading"></div>

## Altogether

An input element is a combination of type, name, and identification. The following code shows an "input" element, wrapped in a "form" element, along with the three _required_ attributes.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<form action="http://www.example.com/login.php" method="post" id="sign-in" class="basic-forms">
    <input type="text" name="username" id="username_input" />
</form>
```


Adding the `<input>` elements makes the `<form>` element more useful. Specifying **input types** is how we ensure that the correct data is entered.
