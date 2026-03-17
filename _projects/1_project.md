---
layout: page
title: Data-driven Differential Equation Identification
description: Identify differential equation from trajectory data
img: assets/img/ident_demo.png
importance: 1
category: work
related_publications: true
---

Data-driven differential equation identification seeks to uncover the governing dynamical models underlying observed phenomena, whether traced from physical experiments or emerging from biological processes.

Our research pursues three interconnected objectives:

- **Algorithm Development** — designing effective, robust, and interpretable methods for recovering differential equations from noisy, sparse, or high-dimensional data.
- **Identifiability Theory** — establishing mathematical frameworks to characterize identifiability conditions for various differential equations.
- **Uncertainty Quantification** — characterizing and propagating uncertainty through the identification pipeline to produce reliable, trustworthy models.

---

## Identification from Noisy Trajectory Data

*Unlike classical regression, the feature matrix consists of differential quantities estimated from single noisy trajectory data. Finite difference schemes inherently amplify noise, making accurate feature estimation and reliable model selection highly challenging. We develop robust computational techniques and rigorous model validation methods to accurately recover governing equations from noisy observations.*

<div style="display:flex;gap:8px;height:280px;margin:1.5rem 0;">
  <div style="flex:1;min-width:60px;overflow:hidden;border-radius:8px;border:1px solid #ccc;transition:flex 0.4s ease;cursor:pointer;position:relative;" onmouseover="this.style.flex=4" onmouseout="this.style.flex=1">
    <img src="/assets/img/noisy_derive.png" style="width:100%;height:100%;object-fit:cover;" />
    <div style="position:absolute;bottom:0;left:0;right:0;background:rgba(0,0,0,0.6);color:white;font-size:12px;padding:6px 8px;">Noisy finite difference</div>
  </div>
  <div style="flex:1;min-width:60px;overflow:hidden;border-radius:8px;border:1px solid #ccc;transition:flex 0.4s ease;cursor:pointer;position:relative;" onmouseover="this.style.flex=4" onmouseout="this.style.flex=1">
    <img src="/assets/img/denoised_derive.png" style="width:100%;height:100%;object-fit:cover;" />
    <div style="position:absolute;bottom:0;left:0;right:0;background:rgba(0,0,0,0.6);color:white;font-size:12px;padding:6px 8px;">Denoised derivative (SDD)</div>
  </div>
  <div style="flex:1;min-width:60px;overflow:hidden;border-radius:8px;border:1px solid #ccc;transition:flex 0.4s ease;cursor:pointer;position:relative;" onmouseover="this.style.flex=4" onmouseout="this.style.flex=1">
    <img src="/assets/img/MTEE.png" style="width:100%;height:100%;object-fit:cover;" />
    <div style="position:absolute;bottom:0;left:0;right:0;background:rgba(0,0,0,0.6);color:white;font-size:12px;padding:6px 8px;">Model validation (MTEE)</div>
  </div>
  <div style="flex:1;min-width:60px;overflow:hidden;border-radius:8px;border:1px solid #ccc;transition:flex 0.4s ease;cursor:pointer;position:relative;" onmouseover="this.style.flex=4" onmouseout="this.style.flex=1">
    <img src="/assets/img/demo_acc.png" style="width:100%;height:100%;object-fit:cover;" />
    <div style="position:absolute;bottom:0;left:0;right:0;background:rgba(0,0,0,0.6);color:white;font-size:12px;padding:6px 8px;">Accuracy vs. noise level</div>
  </div>
</div>

#### References

{% cite he2022robust %}


---

## Varying Coefficient PDE Identification

*Description coming soon.*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/demo_GPIDENT.png" title="Some results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some identification results
</div>

#### References

{% cite he2023group %}
{% cite he2025group %}
{% cite tang2025wg %}

---

## Stochastic ODE/PDE Identification

*Description coming soon.*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/demo_STOCHIDENT.png" title="placeholder" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure placeholder. Replace with your result figure.
</div>

#### References

{% cite cui2025stoch %}

---

## Two-phase PDE Identification

*Description coming soon.*

<div style="display:flex;gap:8px;height:280px;margin:1.5rem 0;">
  <div style="flex:1;min-width:60px;overflow:hidden;border-radius:8px;border:1px solid #ccc;transition:flex 0.4s ease;cursor:pointer;position:relative;" onmouseover="this.style.flex=4" onmouseout="this.style.flex=1">
    <img src="/assets/img/phase1.png" style="width:100%;height:100%;object-fit:cover;" />
    <div style="position:absolute;bottom:0;left:0;right:0;background:rgba(0,0,0,0.6);color:white;font-size:12px;padding:6px 8px;">Phase identification</div>
  </div>
  <div style="flex:1;min-width:60px;overflow:hidden;border-radius:8px;border:1px solid #ccc;transition:flex 0.4s ease;cursor:pointer;position:relative;" onmouseover="this.style.flex=4" onmouseout="this.style.flex=1">
    <img src="/assets/img/phase2.png" style="width:100%;height:100%;object-fit:cover;" />
    <div style="position:absolute;bottom:0;left:0;right:0;background:rgba(0,0,0,0.6);color:white;font-size:12px;padding:6px 8px;">Covering patches(SDD)</div>
  </div>
  <div style="flex:1;min-width:60px;overflow:hidden;border-radius:8px;border:1px solid #ccc;transition:flex 0.4s ease;cursor:pointer;position:relative;" onmouseover="this.style.flex=4" onmouseout="this.style.flex=1">
    <img src="/assets/img/phase3.png" style="width:100%;height:100%;object-fit:cover;" />
    <div style="position:absolute;bottom:0;left:0;right:0;background:rgba(0,0,0,0.6);color:white;font-size:12px;padding:6px 8px;">Evolution based localization</div>
  </div>
  <div style="flex:1;min-width:60px;overflow:hidden;border-radius:8px;border:1px solid #ccc;transition:flex 0.4s ease;cursor:pointer;position:relative;" onmouseover="this.style.flex=4" onmouseout="this.style.flex=1">
    <img src="/assets/img/phase4.png" style="width:100%;height:100%;object-fit:cover;" />
    <div style="position:absolute;bottom:0;left:0;right:0;background:rgba(0,0,0,0.6);color:white;font-size:12px;padding:6px 8px;">Uncertainty quantification</div>
  </div>
</div>

#### References

{% cite yang2026phase %}

---

## Identifiability Theory

*Description coming soon.*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="placeholder" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure placeholder. Replace with your result figure.
</div>

#### References

{% cite he2024howmuch %}
{% cite he2022asymptotic %}
