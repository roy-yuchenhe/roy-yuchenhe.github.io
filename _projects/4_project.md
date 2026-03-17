---
layout: page
title: Image Vectorization and Shape Analysis
description: Variational models for resolution-independent image representation
img: assets/img/ident_demo.png
importance: 1
category: work
related_publications: true
---

Image vectorization converts raster images into parametric representations that 
faithfully encode their prominent geometric features. Unlike pixel-based formats, 
vector representations are resolution-independent, scale-invariant, and amenable 
to geometric analysis. We develop variational methods that produce interpretable 
and compact parametric descriptions of image content, with applications in 
digital illustration, geometric analysis of discrete objects, and scalable 
rendering.
---

## Shape Vectorization by Affine Shortening Flow

*We leverage affine shortening flow to remove pixelization artifacts while preserving the scale-invariant geometric features of image contours. *

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


