---
title: Bootstrap
module: topic-13
permalink: /topic-13/bootstrap/
categories: development
tags:
---

<div class="divider-heading"></div>

<img src="../img/bootstrap.png">An initiative by Twitter, <a href="https://getbootstrap.com/" target="_new">Bootstrap</a> takes credit for introducing responsive design on a large scale. It was the first framework to promote the philosophy of "mobile-first." No longer was designing for smaller screen sizes a separate project in itself; all you needed to do was include the relevant Bootstrap classes, and the design would automatically adjust for different screen sizes (well, almost).

Responsive design in Bootstrap (4.0 vs. 3.0)

Bootstrap achieved responsive design by introducing the idea of a grid. A grid is an invisible partition of the screen into columns (along with the width). For example, if you have three "boxes" you want to position side by side on large screens, but vertically on smaller screens, this is what you’d do:

```html
 <div class="container">
  <div class="row">
    <div class="col-md">
       One of three columns
    </div>
   
    <div class="col-md">
      One of three columns
    </div>

    <div class="col-md">
      One of three columns
    </div>
  </div>
</div>
```

The current popular version of Bootstrap is 4, which was a major overhaul over the 3.3 series. The above syntax is how you'd code in Bootstrap 4, which owes a lot of its elegance to the raw power of Flexbox and other modern layout features supported by browsers directly. In the lower versions of Bootstrap, the grid was defined as a total of 12 columns, which resulted in code such as

```html
<div class="col-md-6 col-lg-4"></div>
```

to make a div take up one-third of the screen width on large-size devices, and half the width in medium-size devices. The syntax now is a lot more pleasant, though it demands familiarity with Flexbox.

**Bootstrap Pros**

There's much to like about Bootstrap, especially for full-stack developers:

**Rapid prototyping:** With Bootstrap, there’s almost no need to spend thought on tricky CSS positioning and browser incompatibilities. All you need to do write out the HTML, and then applying the appropriate CSS classes causes the responsiveness to come alive.

**Large ecosystem:** As of today, Bootstrap has the largest ecosystem among front-end frameworks. The number of website layouts, themes, admin panels, UI components, etc., built using Bootstrap is mind-boggling, and it keeps getting better. For consultants and product companies alike, this means pre-built items and community support will always be plenty.

**Backed by Twitter:** An emerging trend in open source is the rise of projects sponsored by a commercial entity. More often than not, these entities build profitable businesses around their offering. Kotlin (JetBrains), WordPress (Automattic, Inc.), Angular (Google), React (Facebook), etc., are some examples. When a project is backed by an established entity and is not a one-person show, it gives faith to the community (especially the enterprise customers) that the project will have a clear roadmap and long-term future.
A large collection of components: Bootstrap offers, out of the box, almost all the UI components you’re ever likely to need. Navigation, forms, cards, modals, buttons, badges, progress bars, alerts . . . You name it, and Bootstrap has it. For many companies, this practically cuts down the need to have a dedicated front-end team.

**LESS and SASS support:** Among the massively popular CSS frameworks, Bootstrap is the only one that supports both LESS and SASS. Yes, I know, you don’t use LESS (as no self-respecting developer should, right?), but hey, there are massive projects out there that rely on LESS. Of course, you can choose neither and write out your plain CSS files.
Bootstrap Cons
Nothing is without a price, eh? Well, Bootstrap is no exception. Over time, Bootstrap has come under heavy fire by designers and UI experts. Here’s why:

**UX monotony:** The very fact that Bootstrap has such a large collection of built-ins results in websites that look all-too-familiar, and quite honestly, dull. You only need to head over to the official examples to see just how much of an eyesore the defaults are.  Just search for "all bootstrap websites look the same," and you'll know what I mean.

**Styling woes:** Bootstrap is what might be considered an opinionated framework. In other words, it has ideas about layouts, and it makes you work extra hard if you want it to look/behave differently. Consider the default CSS breakpoints for screen widths: a medium-sized screen for Bootstrap is one that starts at a device width of 768px. And what if you want to target, say, the limit of 600px? Well, good luck with that! It’s the same with almost every other component in bootstrap: rows and containers have their default padding, buttons have colors and borders that are very tricky to override without a lot of work, and so on.

<a href="https://geekflare.com/best-css-frameworks/" target="_new"><em>Reference</em></a>
<div class="divider-pg"></div>