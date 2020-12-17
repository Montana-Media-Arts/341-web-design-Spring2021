---
title: Fallback Fonts and Stacks
module: topic-10
permalink: /topic-10/font-fallbacks/
---

<div class="divider-heading"></div>

The font-family property should contain the primary font choice, which is then followed with a comma-delimited, list-of-fonts for the browser to _try_ and load should the primary choice fail for some reason. We consider these **fallback fonts**, in a **font stack**.

For example, the following will cause the browser to first try and load "Comic Sans MS". If the client computer (yours, in this case) does not have a font matching that name, it will then try "Comic Sans", then "Garamond", then "Times", then finally the your default 'serif' font.

The browser will do this by asking the client for the font. If the client doesn't have the font, then the browser will try the next listed font in the chain.

<div class="codepen-embed">
  <p data-height="200" data-theme-id="30567" data-slug-hash="GRqrweP" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Including Fonts, Pt. 2" class="codepen"></p>
</div>

<span class="label label-danger">IMPORTANT:</span> You should not choose fallback fonts carelessly. There are instances where primary fonts load slowly, and the next font in the stack takes its place while processing occurs. Having two unrelated fonts flash in can be jarring, and affect page layout.

See how poorly "Impact" references what will eventually be "Merriweather?"

<img src="../img/font-flop-impact.gif" style="width: 100%; max-width: 625px; margin: auto" alt="two fonts jarring with each other" title="Merriweather vs. Impact"/>

"Georgia" is a much better fallback option (show here with additional character adjustments):

<img src="../img/font-flop-georgia.gif" style="width: 100%; max-width: 600px; margin: auto" alt="two fonts meshing with each other" title="Merriweather vs. Georgia"/>

Visit <a href="https://meowni.ca/font-style-matcher/" target="_new">Font Style Matcher</a> to experiment with finding appropriate fallbacks!
