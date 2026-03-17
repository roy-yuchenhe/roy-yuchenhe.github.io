---
layout: page
title: Image Reconstruction
description: Applications of variational principles and deep learning to image reconstruction. 
img: assets/img/ident_demo.png
importance: 1
category: work
related_publications: true
---

Images encode rich visual information across multiple scales and structures. 
We develop variational and statistical methods to extract, analyze, and process 
this information, with applications spanning image decomposition, reconstruction, 
inpainting, segmentation, and color enhancement.

---

## Tomographic Reconstruction

*Image decomposition aims to separate an image into visually meaningful components whose superposition 
reconstructs the original. Our methods enable each component to be processed,  analyzed, or enhanced independently, with applications in denoising, texture separation, and image editing.*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/demo_GPIDENT.png" title="Some results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some identification results
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/patch_ident.png" title="CaSLR" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Consistent and Sparse Local Regression (CaSLR) identifies varying coefficient PDEs using local patches, within each of which the varying coefficients are well approximated by constants.
</div>

#### References

{% cite he2022robust %}

---


