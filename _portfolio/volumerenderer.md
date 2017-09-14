---
layout: portfolio-post
title: "Volume Renderer"
date: 2015-1-1
tags: 
    - C++
    - OpenGL
    - GLSL

type: game

include: true

images: 
    - "../../assets/images/volfeature.png"
    - "../../assets/images/vol1.png"
    - "../../assets/images/vol2.png"
    - "../../assets/images/vol3.png"

description: "An indirect volume rendering framework for PhD work."
---
{% include image.html file="../../assets/images/vol1.png" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 
 
This project is a supporting part of my Ph.D work. The solo project revolves around the creation of a
real-time rendering framework. The goal of this project was to create a software framework to aid in
real-time rendering research as I found that using an off the shelf engine wouldn’t allow the same versatility
and the same kind of learning opportunities that doing as much of the development as reasonably possible
would.

{% include image.html file="../../assets/images/vol2.png" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 

During this project I’ve gained experience with real-time rendering API’s, cross-platform development
between OSX/Mac OS and Windows with C++, source control software Git, and the cmake build system.
The framework as it exists today is an application for rendering volumes, but the software design allows for
introduction of new capabilities such as new platforms, new rendering API’s, and I/O technologies (such as
VR) with ease.

{% include image.html file="../../assets/images/vol3.png" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 
