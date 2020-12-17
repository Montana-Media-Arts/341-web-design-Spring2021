---
title: 2. Source
module: topic-07
permalink: /topic-07/audio-src/
---

<div class="divider-heading"></div>

The `<audio>` element takes a **source attribute** (`src=""`), which accepts a URL (relative or absolute) to a single audio file.

As with video, it is always recommended you have at least two versions of an audio file, and should use the `<source>` element instead.


## Single-Source

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="66" aria-valuemin="0" aria-valuemax="100" style="width: 66%">
      <span class="sr-only">66% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><audio</span> <span style="color: #79AF33; font-weight: bold;">src="#"</span> <span style="color: #999"> preload controls ></audio></span></p>
  </div>
</div>


<div class="divider-pg"></div>


## Multiple-Source
You can use multiple **source elements**, which specifies to the browser the audio that is available in multiple formats. This is the `<source >` element, and again, it is used _instead_ of the `src=""` attribute of an `<audio>` element.


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="66" aria-valuemin="0" aria-valuemax="100" style="width: 66%">
      <span class="sr-only">66% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><audio</span> <span style="color: #999"> preload controls></span>
        <br>
        <span style="color: #79AF33; font-weight: bold; margin-left: 2em;">&lt;source src="#" type=""&gt;</span>
        <br>
        <span style="color: #79AF33; font-weight: bold; margin-left: 2em;">&lt;source src="#" type=""&gt;</span>
        <br>
    <span style="color: #999;"></audio></span></p>
  </div>
</div>


### Types
When using more than just `.mp3` you should include multiple versions of the file, with decreasing preference. This allows the browser to then use the file format that it supports.

The `<source>` element is an empty element, and accepts the `src=""` attribute to provide the URL to the browser. Use the `type=""` attribute to include the [MIME type](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types), which allows the browser to instantly know if it can play that file.

Here are the types (and codecs when applicable) for the more popular audio filetypes:
- _MP3_ - `type="audio/mpeg"`
- _WAV_ - `type="audio/wav"`
- _OGG_ -`type="audio/ogg; codecs=vorbis"`
