---
title: Styling Backgrounds
module: topic-08
permalink: /topic-08/basic-styling-backgrounds/
---

<div class="divider-heading"></div>

We will get more into styling backgrounds when we formally talk about CSS, but for now, you can do basic color styling using various **background** properties.

Many structural elements can have background property values. If you have a busy page background, it is helpful to add a neutral background to a container (like a div) to keep your content legible and clean.  We just did this in the previous section!


## Adding a Background Color
A color fill can be created using the **background-color property**. You can use many English CSS color names, such as “white,” “orange,” “black,” etc. Check out available color names on <a href="https://www.w3schools.com/cssref/css_colors.asp" target="_blank">W3Schools</a>.

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
<div style="background-color: green;">
```

<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="vYKOOgY" data-default-tab="html,result" data-user="retrog4m3r" data-pen-title="div padding" class="codepen"></p>
</div>


## Adding a Background Image
You can easily generate a pattern on your background by adding a small image (less than 150px or so) and the **background-image property**, where you can use a _relative URL_ to an image in your directory.

<div class="code-heading">
  <span class="html">HTML</span>
</div>

```html
  <body style="background-image: url("#");">
```
**Note** Keep in mind that the image can be something on your site or something external. Just a relative link if it's on your site use a absolute link if it's external (i.e. should start with http or https).

<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="gOMppWr" data-default-tab="html,result" data-user="retrog4m3r" data-pen-title="div padding" class="codepen"></p>
</div>

<div class="divider-pg"></div>


### Example
See how you can add pizazz ( I know, I know, it's busy!) with **background-color** and **background-image** styling!


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="VwjLLWZ" data-default-tab="html,result" data-user="retrog4m3r" data-pen-title="Basic HTML Background Styling" class="codepen"></p>
</div>


Like you saw on the previous page, adding a pixel amount to the `padding: ;` property within your chosen element can give cushion between the boundary of the container and the contents inside.
