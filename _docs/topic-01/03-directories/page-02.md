---
title: Directory Structure
module: topic-01
permalink: /topic-01/directories-structure/
categories: development
tags: directory, file, folder, name
---

<div class="divider-heading"></div>


Directories are hierarchical - directory structural organization resembles a tree, with a single root that branches off into related groups of content.


## Hierarchy
The top-most directory is considered the **root directory**. Whatever current “folder” you are in can be viewed as the **active directory**, and any directories inside that current directory are called **subdirectories.**

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
./root/
└── <i class="far fa-folder-open"></i> directory/ <i class="fas fa-long-arrow-alt-left bounce-x-left"><span>current</span></i>
    └── <i class="far fa-folder-open"></i> subdirectory/
        └── <i class="far fa-file-alt"></i> file.txt
</pre>

<span class="label label-info">Note</span> The root directory in our trees will be shorted to `.` from here-on-out.


<div class="divider-pg"></div>


## Relationships
The web also use familial terms to describe content relationships, such as “grandparent,” “parent,” and “child.” Let's see how this applies to directories:


### Immediate
<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
└── <i class="far fa-folder-open"></i> my-site/ <i class="fas fa-arrows-alt-h bounce-x-left"><span>parent to</span></i><div class="line bounce-x-left"><div class="horizontal-down" style="width: 140px"></div></div>
    └── <i class="far fa-folder-open"></i> content/ <i class="fas fa-arrows-alt-h bounce-x-left"><span>child of</span></i><div class="line bounce-x-left"><div class="horizontal-up" style="width: 115px"></div></div>
        └── <i class="far fa-folder-open"></i> images/
            └── <i class="far fa-image"></i> logo.png
</pre>

In this example, `content/` is a subdirectory of the `my-site/` directory, also referred to as a “child” of that directory (i.e., **child directory**).

The reverse also applies; `content/`, `my-site/` is the **parent directory** to `content/`.

This hierarchy also describes the location of the files. The file `logo.png` is located in its parent directory, `images/`.

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
└── <i class="far fa-folder-open"></i> my-site/
    └── <i class="far fa-folder-open"></i> content/
        └── <i class="far fa-folder-open"></i> images/ <i class="fas fa-long-arrow-alt-left bounce-x-left"><span>parent directory</span></i><div class="line bounce-x-left"><div class="horizontal-down" style="width: 20px"></div></div>
            └── <i class="far fa-image"></i> logo.png  <div class="line bounce-x-left"><div class="horizontal-up" style="width: 135px"></div></div>
</pre>



### Extended
This familial titling can go deeper as well.

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
└── <i class="far fa-folder-open"></i> my-site/ <i class="fas fa-arrows-alt-h bounce-x-left"><span>grandparent to</span></i><div class="line bounce-x-left"><div class="horizontal-down" style="width: 95px"></div></div>
    └── <i class="far fa-folder-open"></i> content/
        └── <i class="far fa-folder-open"></i> images/ <i class="fas fa-arrows-alt-h bounce-x-left"><span>grandchild of</span></i><div class="line bounce-x-left"><div class="horizontal-up" style="width: 45px"></div></div>
            └── <i class="far fa-image"></i> logo.png
</pre>

Here, `images/` is the **grandchild directory** of `my-site/`, which is `images/`'s **grandparent directory.**

This process can extend to great-grandmember, great-great-grandmember, and so forth.
