---
layout: portfolio-post
title: "HTML5 Orrery"
date: 2012-12-1
github-link: orrery
web-link: "/orrery/"
tags: 
    - HTML
    - JavaScript

type: game

include: true

description: "A HTML5 Canvas project depicting the solar system."

images: 
    - "../../assets/images/orreryfeature.png"
---

{% include image.html file="../../assets/images/arc1.png" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 

[Take a look at the Orrery.](https://www.billingsley.dev/orrery/)

The Orrery is a project originally developed in 2012 for my second year module "2D Graphics and User Interfaces", the specification was to build a simple graphics application that showed the orbits of the planets within our solar system.

Rendering with the HTML5 Canvas tag provides a very easy to use sandbox for a variety of 2D graphics techniques, such as Spritesheet animation and Vector graphics. The orrery has a selection of draw modes: Arc mode which renders circles, Line draw mode which renders plants made up of variable line segments, and Sprites/Spritesheets which renders planets using provided sprite images.

{% include image.html file="../../assets/images/orrery1.png" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 

The user can zoom in and out of the canvas, modify the time settings, and pause the update of the rendering, cycle through the rendering modes, change the path of the orbit between circular/elliptical, toggle the orbit path line, and toggle the settings tooltip.
