---
layout: portfolio-post
title: "Sand Globe"
date: 2014-1-1
tags: 
    - C++
    - DirectX 11
    - HLSL

type: game

include: true

images:
    - "../../assets/images/globefeature.jpg"

description: "A DirectX 11 graphics project."

---

{% include image.html file="../../assets/images/globefeature.jpg" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 

This project was produced for the Masters module "Real-Time Graphics" which I enrolled on as part of the University of Hull's Post Graduate Training Scheme for PhD students. The task was to produce a C++ DirectX 11 application that presented a "Sandy Snow Globe" scene, this is a take on the classic Snow Globe, where the Globe contains a Desert that has a night/day and season cycle.


{% include image.html file="../../assets/images/globerain.jpg" style="width:600px; position: relative; left: 50%;margin-left: -300px" %} 

In the scene, the camera can move freely inside and out of the Globe, the Globe contains a Desert filled with Cactii, The Cactii grow over time, especially during the rain season. In the globe there are 4 seasons, with the first two seasons having rain, the third being dry and the fourth being snowy.

{% include image.html file="../../assets/images/globesnow.jpg" style="width:600px; position: relative; left: 50%;margin-left: -300px" %} 

The day/night cycle is provided by a rotating directional light. The weather effects are produced using a particle system that renders particles using Instanced rendering. The Globe is translucent from the outside but opaque from the inside which is achieved using a mixture of flipped normals on the globe, and face culling. A basic UI is provided using the AntTweakBar library.

{% include image.html file="../../assets/images/globe1.png" style="width:600px; position: relative; left: 50%;margin-left: -300px" %} 
