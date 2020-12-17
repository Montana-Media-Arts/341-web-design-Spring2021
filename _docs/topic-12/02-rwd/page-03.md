---
title: Setting Viewport
module: topic-12
permalink: /topic-12/rwd-viewport/
categories: development
tags:
---

<div class="divider-heading"></div>

## HTML | Viewport meta tag for Responsive Web Design

Let's review what viewport is.

**What is Viewport?** 

A Browser’s viewport is the area of web page in which the content is visible to the user. The viewport does not have the same size, it varies with the variation in screen size of the devices on which the website is visible. For a laptop, the viewport has a larger size as compared to a smartphone or tablet.

**Note:** When a page is not made responsive for smaller viewports it looks bad or even breaks on smaller screen. To fix this problem introduce a responsive tag to control the viewport. This tag was firstly introduced by Apple Inc. for Safari iOS.

**Syntax:**

```html
<meta name="viewport" content= "width=device-width, initial-scale=1.0"> 
```

This is the common setting of viewport used in various mobile-optimized websites. The width property governs the size of the viewport. It is possible to set it to a specific value `“width=600”` in terms of CSS pixels. Here it is set to a special value `width= device-width”` which is the width of the device in terms of CSS pixels at a scale of 100%. The initial-scale property governs the zoom level when the page is loaded for the first time.

**Note:** The meta tag should be added in the head tag in HTML document.

A Responsive tags has the following attributed:

**width**: Width of the virtual viewport of the device.
**height**: Height of the virtual viewport of the device.
**initial-scale**: Zoom level when the page is first visited.
**minimum-scale**: Minimum zoom level to which a user can zoom the page.
**maximum-scale**: Maximum zoom level to which a user can zoom the page.
**user-scalable**: Flag which allows the device to zoom in or out.(value= yes/no).

Example:

```html
<!DOCTYPE html> 
<html> 
    <head> 
        <title>GeeksforGeeks</title> 
        <meta charset="utf-8" name="viewport" 
        content= "width=device-width, initial-scale=1.0"> 
        <style> 
            .gfg { 
                font-size:40px; 
                font-weight:bold; 
                color:green; 
                text-align:center; 
            } 
            .geeks { 
                font-size:17px; 
                text-align:center; 
            } 
            p { 
                text-align:justify; 
            } 
        </style> 
    </head> 
    <body> 
        <div class = "gfg">GeeksforGeeks</div> 
        <div class = "geeks">A computer science portal for geeks</div> 
          
          
        <p>Prepare for the Recruitment drive of product based companies like 
        Microsoft, Amazon, Adobe etc with a free online placement preparation 
        course. The course focuses on various MCQ's & Coding question likely 
        to be asked in the interviews & make your upcoming placement season  
        efficient and successful. </p> 
        <p>An extensive Online Test Series for GATE 2019 to boost the  
        preparation for GATE 2019 aspirants. Test series is designed  
        considering the pattern of previous years GATE papers and ensures 
        to resemble with the standard of GATE. This Test Series will help 
        the aspirants track and improve the preparation through questions 
        of various difficulty levels. There will be two Test Series  
        covering the whole syllabus of GATE, including Mathematics and 
        Aptitude. Test Series I will cover the basic and medium difficulty,  
        whereas in Test Series II difficulty will be slightly higher. </p> 
    </body> 
</html>             
```

<a href="https://www.geeksforgeeks.org/html-viewport-meta-tag-for-responsive-web-design/" target="_new"><em>Reference</em></a>

### Size Content to The Viewport
Users are used to scroll websites vertically on both desktop and mobile devices - but not horizontally!

So, if the user is forced to scroll horizontally, or zoom out, to see the whole web page it results in a poor user experience.

Some additional rules to follow:

1. **Do NOT use large fixed width elements** - For example, if an image is displayed at a width wider than the viewport it can cause the viewport to scroll horizontally. Remember to adjust this content to fit within the width of the viewport.

2. **Do NOT let the content rely on a particular viewport width to render well** - Since screen dimensions and width in CSS pixels vary widely between devices, content should not rely on a particular viewport width to render well.

3. **Use CSS media queries to apply different styling for small and large screens** - Setting large absolute CSS widths for page elements will cause the element to be too wide for the viewport on a smaller device. Instead, consider using relative width values, such as width: 100%. Also, be careful of using large absolute positioning values. It may cause the element to fall outside the viewport on small devices.

<a href="https://www.w3schools.com/css/css_rwd_viewport.asp" target="_new"><em>Reference</em></a>