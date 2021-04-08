---
title: Foundation
module: topic-13
permalink: /topic-13/foundation/
categories: development
tags:
---

<div class="divider-heading"></div>

<img src="../img/foundationcss.jpg">

If technologies were religions, the Foundation and Bootstrap guys would be out for each other’s blood. No discussion of modern CSS frameworks is complete without mentioning Foundation, so here we go.

Head over to the <a href="https://get.foundation/" target="_new">Foundation website</a>, and you can’t help but notice the byline: "The most advanced responsive front-end framework in the world." At first glance, it looks like a tall claim to go with a marketing campaign.

However, adherents of the Foundation framework know there’s at least some truth to that. Foundation was developed to go naturally with the Rails framework, and several of the Rails’ “zen-like” guiding principles can be seen at work.

For instance, if you wanted a row that contained two elements on small screens, three on medium, and four on large ones, the equivalent code in Foundation will look like this:

```html
 <ul class="small-block-grid-2 medium-block-grid-3 large-block-grid-4">
  <li><!-- Your content goes here --></li>
  <li><!-- Your content goes here --></li>
  <li><!-- Your content goes here --></li>
  <li><!-- Your content goes here --></li>
  <li><!-- Your content goes here --></li>
  <li><!-- Your content goes here --></li>
</ul>
```

As compared to earlier Bootstrap versions, this very intuitive and easy to memorize. No more twelve column grids and figuring out what 4/12 is supposed to be.

While Foundation is much less popular than Bootstrap, it's a trade secret for many expert front-end developers.

**Pros of the Foundation Framework**

Foundation has some unusual characteristics out of all the CSS frameworks we are going to consider in this article:

**Full tooling:** It’s technically wrong to say that Foundation is a CSS framework. I mean, it is, but it’s been built as a large and modular collection of tools that aims to solve almost all kinds of front-end problems. There are separate framework offerings for websites and emails, heavily optimized for their respective domains. Foundation also comes with a command-line interface (CLI), which will sound like music to the ears of developers used to working with Webpack or other module bundlers.

**Extreme flexibility:** Unlike Bootstrap, Foundation was built to give the front-end developer full control over their UIs. As a result, Foundation will feel bland and enormously complex to the newcomer. However, the reason is that Foundation doesn’t force any style language on you, but aims to be just what it is: an excellent CSS framework.

**More than just UI components:** While Foundation has the usual collection of UI elements, it goes much beyond the call of duty. The developers have included an advanced responsive image system, a pricing table component (yes, the one used to show various pricing plans), form-validation, right-to-left support, responsive embeds, and more. I'd like to emphasize again that this is an overkill for most simple websites, but for large ones, it's a boon the experienced developers will recognize.

**Training and consulting:** Now, while Bootstrap is created by Twitter, it’s a side project and a very small part of the overall picture. The company behind Foundation (ZURB), however, is committed to using, developing and promoting it. Training courses and professional consulting are offered for large customers, which is great for companies that are targeting massive projects and are willing to pay.

**Cons of the Foundation Framework**

The strengths of one framework become its weaknesses when viewed from the opposite point of view. Here's why the Foundation may not be the best choice for your project:

**Small(er) community:** The Foundation community is much smaller than that of Bootstrap, and if you're trying something exotic and get stuck, the chances of finding relevant help are lower. However, I would add that for all practical purposes; there's enough of a community out there. It’s just that it's several orders of magnitude smaller than Bootstrap’s, so you might not find solutions instantly.

**Complexity:** If you're used to Bootstrap or something simple, or worse, to vanilla CSS, Foundation will feel like an infinite explosion of complexity. Layers within layers, components with components, endless customization options. Foundation has a very different aim.

**Too many options:** Sometimes you just want to be productive and worry about perfection later. During such times, it's frustrating to be presented with too many options with minor variations. For example, think of having to order a Subway sandwich when you're so hungry painstakingly you could eat mud. Naturally, Foundation isn't for times like that.

**Talent availability:** Since Foundation is (much) less popular than Bootstrap, the available talent is much less. As a general rule, any new hire is almost likely to know Bootstrap but won't have a clue about Foundation. Learning takes time, and it's a luxury not all teams can have.

<a href="https://geekflare.com/best-css-frameworks/" target="_new"><em>Reference</em></a>

<div class="divider-pg"></div>