---
layout: post
title: "Personal Website"
date: 2017-1-1
github-link: rbillingsley.github.io
tags: 
    - Ruby
    - Jekyll
    - HTML
    - CSS
---
{% if page.github-link %}
    {% include icon-github.html username=site.github_username repo_link=page.github-link %}
{% endif %}

{% include image.html url=site.url
max-width="200px" file="/assets/images/test.png" alt="Test image"
caption="" %} 

Placeholder. This website is built using Jekyll and hosted on GitHub Pages.

<!--excerpt-->