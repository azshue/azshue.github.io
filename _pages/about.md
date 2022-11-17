---
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About me     
  I am a 4-th year Ph.D. Student in the Department of Computer Science at the University of Maryland, College Park (UMD). As a research assisstant at UMD, I work with my Ph.D. advisor Professor [Tom Goldstein](https://www.cs.umd.edu/~tomg/). My research focuses on developing practical machine learning (ML) models that can generalize to real-world data, which includes a wide range of data distributions. I am interested in studying this problem for different applications, including computer vision and multi-modal learning. 


## Publications
  <ul>
    {% for post in site.publications reversed %}
        {% include archive-single-cv.html %}
  {% endfor %}
  </ul>