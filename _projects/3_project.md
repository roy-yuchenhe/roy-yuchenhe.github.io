---
layout: page
title: Image Reconstruction
description: Applications of variational principles and deep learning to image reconstruction. 
img: assets/img/image_rec_demo.png
importance: 1
category: work
related_publications: true
---

Image reconstruction is a fundamental inverse problem arising across diverse scientific and engineering domains — from medical imaging and remote sensing to computational photography. Given incomplete, noisy, or indirectly observed measurements, the goal is to recover the underlying image faithfully. We develop robust variational models and efficient algorithms to address challenging reconstruction problems, with an emphasis on theoretical guarantees and practical performance. 

---

## Tomographic Reconstruction

*Tomographic reconstruction aims at recovering the internal structure of an object from a collection of projected measurements taken at different angles. The problem is inherently ill-posed. We develop variational and deep learning models that incorporate prior knowledge of the underlying structure to achieve high-quality reconstruction from limited and possibly dynamical data.*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/brain_reconstruct.png" title="MRI-guided brain intervention" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Real-time MRI-guided brain intervention based on deep unrolled neural network.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/NINRF_demo.png" title="NINRF" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Proposed non-negative INR factorization model for dynamic PET reconstruction.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DSP-CTR-demo.png" title="DSP-CTR" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Robust dynamic SPECT reconstruction with scarce angular and limited temporal sampling using  Deep Spatial Prior with Continuous Temporal Representation. 
</div>

#### References

{% cite he2023deep %}
{% cite zhang2025dynamic %}
{% cite wu2026robust %}

---


