---
layout: page
title: Variational Image Decomposition
description: Variational models for image decomposition
img: assets/img/img_process_demo.png
importance: 1
category: work
related_publications: true
---

Image decomposition aims to separate an image into visually meaningful components whose superposition 
reconstructs the original. Our methods enable each component to be processed,  analyzed, or enhanced independently, with applications in denoising, texture separation, and image editing.

---

## Image Decomposition

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/demo_euler.png" title="Euler's elastica-based image decomposition" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    We developed an efficient and effective three-component (cartoon-smooth-oscillation) image decomposition variational model.
    [<a href="https://github.com/roy-yuchenhe/elastica-image-decomposition" target="_blank">Code</a>]
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


