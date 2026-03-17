---
layout: page
title: Mathematical and Deep Learning for Image Processing
description: Diverse applications of mathematical tools and deep learning techniques to image processing
img: assets/img/img_process_demo.png
importance: 1
category: work
related_publications: true
---

Images encode rich visual information across multiple scales and structures. 
We develop variational and statistical methods to extract, analyze, and process 
this information, with applications spanning image decomposition, reconstruction, 
inpainting, segmentation, and color enhancement.

---

## Image Decomposition

*Image decomposition aims to separate an image into visually meaningful components whose superposition 
reconstructs the original. Our methods enable each component to be processed,  analyzed, or enhanced independently, with applications in denoising, texture separation, and image editing.*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/demo_euler.png" title="Euler's elastica-based image decomposition" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    We developed an efficient and effective three-component (catroon-smooth-oscillation) image decomposition variational model. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/vectorialTV_demo.png" title="Color image decomposition using Vectorial total symmetric variation (VTSV)" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    We proposed a family of Vectorial Total Symmetric Variation (VTSV) for efficiently coupling channel information during decomposition.
</div>

#### References

{% cite he2026vectorial %}
{% cite he2025image %}
{% cite he2025euler %}

---


