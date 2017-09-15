---
layout: portfolio-post
title: "Pumpkin Party"
date: 2013-12-1
tags: 
    - GLSL
    - RenderMonkey

type: game

include: true

images: 
    - "../../assets/images/pumpkinfeature.jpg"

description: "A shader based graphics project for learning GLSL."
---

{% include image.html file="../../assets/images/pumpkinfeature.jpg" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 

This project was produced for my third year module "Games Programming and Advanced Graphics". This project is a scene produced in the Shader Workbench RenderMonkey, it's produced using only the available example primitives and added textures. The specification was to build a scene of a "Halloween Pumpkin Party" with the Pumpkins showcasing a variety of shader effects.

{% include image.html file="../../assets/images/pcollection.jpg" style="width:700px; position: relative; left: 50%;margin-left: -350px" %} 

The Pumpkins are created by transforming a Sphere and applying textures, Height Maps, Bump Maps and using Parallax Mapping. In the above picture, there's an example of each technique, as well as the techniques being applied to non standard shapes such as a Torus and the Utah Teapot. There are also examples of Pumpkins that reflect and refract the environment map. Stencils are also used to create Pumpkins with animated burning fires inside to create a Pumpkin lantern, on the back row there are also examples of bouncing and pulsating pumpkins, where the animations are shader driven.

{% include image.html file="../../assets/images/pfirework.jpg" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 

To finish the scene the Pumpkins are joined by a firework effect, and they are enveloped in a fog effect, this was achieved using a mixture of a set of textured planes and a screenspace moving smoke texture to provide the illusion of volumetric animated fog. Undertaking this project was enjoyable as it removed the usual stresses of implementing the APIs and allowed me to concentrate on exploring the power of shaders.
