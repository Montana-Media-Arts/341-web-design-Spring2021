---
title: Grid View
module: topic-12
permalink: /topic-12/rwd-gridview/
categories: development
tags:
---

<div class="divider-heading"></div>

## Building a Responsive Grid-View

Lets start building a responsive grid-view.

First ensure that all HTML elements have the box-sizing property set to border-box. This makes sure that the padding and border are included in the total width and height of the elements.

Add the following code in your CSS:

```css
* {
    box-sizing: border-box;
  }
```

The following example shows a simple responsive web page, with two columns:

```css
.menu {
  width: 25%;
  float: left;
  
}
.main {
  width: 75%;
  float: left;
}

.display-inline-block {
    display: inline-block;
}

.menu-item:hover {
    background-color: gold;
    color: #333;
}

p{
  text-align: justify;
}
```

```html
<div class="menu">
   <div class="menu-item display-inline-block">
      Home
   </div>
   <div class="menu-item display-inline-block">
      Services
   </div>
   <div class="menu-item display-inline-block">
      About
   </div>
   <div class="menu-item display-inline-block">
      Contact
   </div>
</div>

<div class="main">
  <h1>Main Information</h1>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
</div>
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="OJXoqPN" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Grid-View 2 Column" class="codepen"></p>
</div>

What if we want to use a responsive grid-view with 12 columns, to have more control over the web page.

First calculate the percentage for one column: 100% / 12 columns = 8.33%.

Then make one class for each of the 12 columns, class="col-" and a number defining how many columns there are:


```css
.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}
```

We should also apply the following to all the classes

```css
[class*="col-"] {
  float: left;
  padding: 15px;
}
```

```css
.row::after {
  content: "";
  clear: both;
  display: table;
}
```

```html
<div class="row">
  <div class="col-1">
    <div class="menu-item display-inline-block">
        Home
    </div>
    <div class="menu-item display-inline-block">
        Services
    </div>
    <div class="menu-item display-inline-block">
        About
    </div>
    <div class="menu-item display-inline-block">
        Contact
    </div>
  </div>

  <div class="col-11">
    <h1>Main Information</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
  </div>
</div>
```

In this example, let's look at shrinking the size of the menu and then letting the rest of the content fill the page.  If the screen is too small, then it will wrap to the next line instead of crowding the menu.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="ExyeMKO" data-default-tab="css,result" data-user="retrog4m3r" data-embed-version="2" data-pen-title="Grid-View 12 Column" class="codepen"></p>
</div>

<a href="https://www.w3schools.com/css/css_rwd_grid.asp" target="_new"><em>Reference</em></a>


