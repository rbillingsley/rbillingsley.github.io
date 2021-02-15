---
layout: portfolio-post
title: "Personal Website"
date: 2017-1-1
github-link: rbillingsley.github.io
tags: 
    - Jekyll
    - Liquid
    - HTML
    - CSS/SASS

type: misc

include: true

images: 
    - "../../assets/images/webfeature.png"

description: "Personal Website built to house my CV and portfolio."
---

This website has been built to house my CV, portfolio, contact information, and eventually a blog for technical writing. The design is simple and minimal to focus on the content, this is a slightly altered version of the Jekyll theme "Minima". This website is built using Jekyll and is hosted on GitHub-Pages.

{% include image.html file="../../assets/images/webfeature.png" style="width:400px; position: relative; left: 50%;margin-left: -200px" %} 

The alterations include the custom portfolio pages, this was done so that the portfolio pieces exist in their own collection on the site, which allows me to use Jekyll's built in powerful blog infrastructure rather than overloading it for my portfolio. These additional pages are built using HTML and Liquid. Additional HTML fragment files are used to include images, the icons for GitHub links, and the listing of the technologies used on each project. Building this website has also given me some experience with [SASS](http://sass-lang.com/) and [TravisCI](https://travis-ci.org/).
