---
permalink: /
title: 
excerpt:
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About me     
   I am a 4th-year Ph.D. candidate in the Department of Computer Science at the University of Maryland, College Park (UMD). As a research assistant at UMD, I work with my Ph.D. advisor Dr.[Tom Goldstein](https://www.cs.umd.edu/~tomg/). My research goal is to develop practical machine learning/deep learning (ML/DL) models that can generalize to real-world data. Relevant research directions include robustness to distribution shift, out-of-distribution generalization, etc. I am interested in studying these problems on different applications, including computer vision and multimodal learning.      

<!-- ## News    
  * I'm attending NeurIPS this year in person.  -->

## Publications
  <ul>
    {% for post in site.publications reversed %}
        {% include archive-single-cv.html %}
  {% endfor %}
  </ul>