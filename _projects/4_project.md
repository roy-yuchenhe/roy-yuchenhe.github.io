---
layout: page
title: Image Vectorization and Shape Analysis
description: Variational models for resolution-independent image representation
img: assets/img/vec_demo.png
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

*We leverage affine shortening flow to remove pixelization artifacts while preserving the scale-invariant geometric features of image contours.*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fish_demo.png" title="Comparison" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Compared to commercial software, our approach yields more interpretable and efficienct vector graphics.
</div>

#### References

{% cite he2023binary %}
{% cite he2022silhouette %}
{% cite he2021accurate %}

---

## Topological-aware Color Image Vectorization

*By careful analysis of local topological patterns in raster images, we develop a surgical strategy for image vectorization that preserves prominent singularities with high fidelity.*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/topo_vec_demo.png" title="Vectorization of pixel arts" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our approach produces vector graphics with high fidelity.
</div>

#### References

{% cite he2023binary %}
{% cite he2022silhouette %}
{% cite he2021accurate %}
