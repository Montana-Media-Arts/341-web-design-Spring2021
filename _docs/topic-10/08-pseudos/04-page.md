---
title: Setting States
module: topic-10
permalink: /topic-10/pseudo-states/
---

<div class="divider-heading"></div>

You'll notice on the previous page's example that the style of the link reacted when you moused-over it. This provides a visual indicator to a visitor that the link is still active, should they look for it again after it was visited (set to gray out in the `:visited` state).

Many pseudo-classes react to events like these, which we generally refer to as **states.**

The most common pseudo-class states:
- `:hover` (event is triggered when mouse hovers over)
- `:active` (event is triggered while element is selected)

<div class="code-heading">
  <span class="css">CSS</span>
</div>

```css
selector:hover {}
selector:active {}

/* The word selector in the above is replaced with
the normal CSS selectors used to identify elements. */
p:hover {
  color: green;
}
```

<span class="label label-info">NOTE:</span> Any pseudo-class that relies upon mouse information (such as the ones below) will not translate to mobile devices.

### “When would I use states?”

_“Quite often!”_ Many elements can utilize hover states, although it is most commonly used with links.

Buttons are built with states. Active states make a button feel more real by slightly changing the color when the user presses it. But this can be used for any pressed effect.

If the example below, the button utitlizes `:hover` to change the appearance of the text, and `:active` to give the experience of a button press.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="qBNRgYd" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Pseudo-Classes, Pt. 3" class="codepen"></p>
</div>
