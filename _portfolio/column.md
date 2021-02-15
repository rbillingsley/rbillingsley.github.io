---
layout: portfolio-post
title: "The Column"
date: 2013-5-1
tags: 
    - C#
    - OpenGL
    - GLSL
    - OpenTK

type: game

include: true

images:
    - "../../assets/images/columnfeature.jpg"

description: "A C# OpenGL 3D Graphics showcase."
---

{% include image.html file="../../assets/images/columnportrait.jpg" style="width:200px; position: relative; left: 50%;margin-left: -100px" %} 

The Column is a project produced for my second year module "3D Graphics & Simulation", the spec was to create a physics simulation where balls are pushed into the top of a sealed column by three portals. The portals produced balls of different colour and mass. The column is split into four areas, the portal area, the axis aligned cylinder area, the non axis aligned cylinder area, and the "Sphere of Doom" area.

{% include image.html file="../../assets/images/columnsphere.jpg" style="width:550px; position: relative; left: 50%;margin-left: -275px" %} 

The initial portal area contains three portals that produces ball, this area produces many sphere on sphere collisions. The next two areas are designed to produce sphere on cyclinder collisions and sphere on plane collisions. The final area contains a "Sphere of Doom" this sphere shrinks the spheres on contact, if a sphere makes a complete collison withe the "Sphere of Doom" then it is shrunk until it's destroyed, balls respawn at the top of the system if the make it to the ground plane of the column.

{% include image.html file="../../assets/images/columncylinder.jpg" style="width:550px; position: relative; left: 50%;margin-left: -275px" %} 

The rendering of this scene uses a variety of meshes, different coloured spheres, and textured portals, walls and spheres. The user also has arcball mouse, and keyboard camera controls to observe the scene. The user can toggle backface culling to observe the scene from outside of the box, as can be seen in the first screenshot. Objects in the scene are lit by a Phong directional light.

{% include image.html file="../../assets/images/columnportal.jpg" style="width:550px; position: relative; left: 50%;margin-left: -275px" %} 
