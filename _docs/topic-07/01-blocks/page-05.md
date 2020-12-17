---
title: Sectioning with Spans
module: topic-07
permalink: /topic-07/html-spans/
---

<div class="divider-heading"></div>

The **span element** is the inline equivalent of the `<div>` element.

<div class="container-row">
  <img src="../img/legos-spans.png" alt="stacked building blocks with stickers representing span elements" title="Blocks can have multiple spans!" style="float: right; width: 150px; margin-top: 0;" />

  <p>This means that spans can exist within divs, and do not create full-width blocks. It serves to identify or group content together that requires organization or extra styling. You can have <b>multiple span elements</b> inside a div.</p>

  <p>One specific use for the <code>&lt;span&gt;</code> element is to identify text that needs to appear visually unique on the rendered HTML page.</p>

  <p>As with the <code>&lt;div&gt;</code> element, the <code>&lt;span&gt;</code> element should include a class or id attribute to provide:</p>

  <ul>
    <li>a reference to styling code</li>
    <li>and/or information to developers about the inner content</li>
  </ul>
</div>

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p>Use <span>the span attribute</span> within block-level elements, like paragraphs.</p>


<!-- For example... -->
<div id="long-blue" class="long-block">
  <p>
    A block with a <span class="white-square">white square</span>,
    <span class="gray-square">gray square</span>,
    another <span class="white-square">white square</span>,
    and <span class="circle">circle</span> on it.
  </p>
</div>

<div id="short-red" class="long-block">
  <p>
    A block with a <span class="black-circle">black circle</span> and <span class="rectangle">rectangle</span> on it.
  </p>
</div>
```