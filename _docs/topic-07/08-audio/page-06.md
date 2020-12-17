---
title: Review&#58; The Audio Element
module: topic-07
permalink: /topic-07/audio-element-review/
---

<div class="divider-heading"></div>


A full audio element is a combination of resource location and access attributes:


<div class="external-embed" style="text-align: center;">
	<h3 style="color: #E95420">Smooth Jazz</h3>
	<audio preload controls>
    <source src="../media/duckett-audio.ogg" type="audio/ogg; codecs=vorbis" />
    <source src="../media/duckett-audio.mp3" type="audio/mpeg" />
    <p>A sample of smooth jazz music.</p>
    <p>Sorry, your browser does not support our audio format.</p>
	</audio>
</div>


## Single-Source


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<audio src="#" preload controls></audio>


<!-- For example... -->
<audio src="./media/duckett-audio.ogg" preload controls>
  <p>Sorry, your browser does not support our audio format.</p>
</audio>
```


<div class="divider-pg"></div>


## Multiple-Source


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<audio preload controls>
  <source src="#" type="">
  <source src="#" type="">
</audio>


<!-- For example... -->
<audio preload controls>
  <source src="./media/duckett-audio.ogg" type="audio/ogg; codecs=vorbis" />
  <source src="./media/duckett-audio.mp3" type="audio/mpeg" />
  <p>A sample of smooth jazz music.</p>
  <p>This browser does not support our audio format.</p>
</audio>
```
