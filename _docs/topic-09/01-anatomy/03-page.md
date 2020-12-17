---
title: Property and Value
module: topic-09
permalink: /topic-09/property-value/
---

<div class="divider-heading"></div>

Inside the declaration, one specifies how to style the selected element with property-value pairs.

The pair is separated with a colon (`:`).

Additional declarations are separated with a semicolon (`;`), and are typically placed on new lines.

### Property

The **property** is the aspect about the element that one wants to change, i.e. background-color, color, font-family, etc.

### Value

The **value** defines how to change a property; for example, 'red', 'Arial', etc.

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
p {
    property-1: value;
    property-2: value;
}
```

<span class="label label-info">NOTE:</span> As a rule, there should be no spaces in the property or the value. Each will be a non-breaking set of characters, with multi-word properties created using hyphens (`-`).
