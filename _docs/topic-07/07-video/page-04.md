---
title: 2. Source
module: topic-07
permalink: /topic-07/video-src/
---

<div class="divider-heading"></div>

The `<video>` element takes a **source attribute** (`src=""`), which accepts a URL (relative or absolute) to a single video file.

It is always recommended you have at least two versions of a video file, and should use the `<source>` element instead, which is described below.


## Single-Source

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%">
      <span class="sr-only">40% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><video</span> <span style="color: #79AF33; font-weight: bold;">src="#"</span> <span style="color: #999">poster="#" width="..." height="..." preload controls ></video></span></p>
  </div>
</div>


<div class="divider-pg"></div>


## Multiple-Source
You can use multiple **source elements**, which specifies to the browser that the video is available in multiple formats. This is the `<source>` element, and again, it is used _instead_ of the `src=""` attribute of a `<video>` element.

<span class="label label-info">Note</span> Due to a bug on the iPad, you should provide the MP4 video as the first format.

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%">
      <span class="sr-only">40% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><video</span> <span style="color: #999"> poster="#" width="..." height="..." preload controls></span>
        <br>
        <span style="color: #79AF33; font-weight: bold; margin-left: 2em;">&lt;source src="#" type=""&gt;</span>
        <br>
        <span style="color: #79AF33; font-weight: bold; margin-left: 2em;">&lt;source src="#" type=""&gt;</span>
        <br>
    <span style="color: #999;"></video></span></p>
  </div>
</div>

### Types
After the source, you'll notice the **type attribute**.

Use the `type=""` attribute to tell the browser what format the video is in. Otherwise, it will download some of the video to see if it can play the file, find that it cannot, and then try the next one until it has exhausted all options or found a valid file format. **This takes time and bandwidth!**

The codec that was used to encode the video is supplied within the type attribute, following the video file type, separated by a semicolon (`;`). Here are the types and codecs for the more popular video filetypes:
- _MP4_ - `type='video/mp4; codecs="avc1.4D401E, mp4a.40.2"'`
- _WebM_ -`type='video/webm; codecs="vp8.0, vorbis"'`
- _OGG_ - `type='video/ogg; codecs="theora, vorbis"'`
