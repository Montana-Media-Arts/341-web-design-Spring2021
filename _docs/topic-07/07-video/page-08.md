---
title: Review&#58; The Video Element
module: topic-07
permalink: /topic-07/video-element-review/
---

<div class="divider-heading"></div>


A full video element is a combination of resource location, poster, width, height, and access attributes:

<div class="external-embed" style="text-align: center;">
	<h3 style="color: #E95420">Smooth Puppy</h3>
	<video poster="../media/duckett-puppy-poster.png" width="400" height="320" preload controls>
		<source src="../media/duckett-puppy.mp4" type='video/mp4;codecs="avc1.42E01E, mp4a.40.2"'>
		<source src="../media/duckett-puppy.webm" type='video/webm;codecs="vp8, vorbis"'>
		<p>A video of a puppy playing in the snow.</p>
		<p>Sorry, your browser does not support the video tag.</p>
	</video>
</div>


## Single-Source


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<video src="#" poster="#" width="" height="" preload controls></video>


<!-- For example... -->
<video src="./media/duckett-puppy.mp4" poster="./images/duckett-puppy-poster.png" width="768" height="576" preload controls>
  <p>Sorry, your browser does not support the video tag.</p>
</video>
```


<div class="divider-pg"></div>


## Multiple-Source


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<video poster="#" width="" height="" preload controls>
  <source src="#" type="">
  <source src="#" type="">
</video>


<!-- For example... -->
<video poster="./images/duckett-puppy-poster.png" width="768" height="576" preload controls loop>
  <source src="./media/ducket-puppy.mp4" type='video/mp4;codecs="avc1.42E01E, mp4a.40.2"'>
  <source src="./media/duckett-puppy.webm" type='video/webm;codecs="vp8, vorbis"'>
  <p>A video of a puppy playing in the snow.</p>
  <p>Sorry, your browser does not support the video tag.</p>
</video>
```
