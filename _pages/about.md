---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

(The site is under construction! Sorry for (temporarily) limited information.)


I am a Ph.D. candidate in applied physics at [CEITEC](https://www.ceitec.eu/) in Brno, Czech Republic. I also collaborate with [KASL](https://www.kasl.ai/) and was previously a visiting Ph.D. student at the University of Cambridge, advised by David Krueger.

My current research focuses on foundational topics in machine learning (ML), where I am mostly interested in understanding deep learning through empirical and theoretical methods, usually grounded in physics. The main motivation is to achieve interpretable and safe ML/AI for science and general use. My work includes various topics in overparameterization, loss-landscape geometry, sparsity, and adversarial robustness of deep networks.
Prior to that, I worked on interpretable machine learning applied to spectroscopic data and physics-inspired learning.

When I'm not busy with ML experiments, you can find me bouldering or cycling. I also enjoy hiking, playing guitar, and reading physics books from my vast collection.

---
**News**
*Jan. 2025:* Input space mode connectivity was accepted to ICLR 2025.

*Oct. 2024:* Input space mode connectivity was accepted for an [oral presentation](https://neurips.cc/virtual/2024/workshop/84741#collapse-sl-109173) at [SciForDL](https://scienceofdlworkshop.github.io/) at NeurIPS 2024.

*Aug. 2024:* I am attending the [IAIFI summer school](https://iaifi.org/phd-summer-school.html) and [workshop](https://iaifi.org/summer-workshop.html) at MIT, where I will give a talk on input space mode connectivity.

*June 2024:* I am visiting [KASL](https://www.kasl.ai/) $\subset$ [CBL](https://mlg.eng.cam.ac.uk/), University of Cambridge for four months (advised by D. Krueger).

*May 2024:* I will be at [Youth in High Dimensions](https://indico.ictp.it/event/10478) workshop at ICTP in Trieste, Italy.

---
**Research interests**
* Machine learning foundations
  * overparametrization, double descent, NTK 
  * loss-landscape symmetries, mode connectivity
  * sparsity, lottery tickets
* ANN interpretability (for spectroscopic data)
  * feature visualization, optimal manifold
  * sparsity for (mechanistic) interpretability
  * custom loss penalization 
* AI safety
  * LLM jailbreaking (defenses)


---
**Current projects**
<div style="display: flex;">
  <!-- Image on the left -->
  <img src="/images/mode_connectivity.png" alt="Description" style="width: 250px; height: 150;">

  <!-- Content on the right -->
  <div style="margin-left: 30px;">
    <h3>Input space mode connectivity</h3>  <!-- Title -->
    <p>We generalized the concept of loss landscape mode connectivity to the input space of deep neural networks.</p>  <!-- Description -->
    <a href="https://openreview.net/forum?id=3qeOy7HwUT">ICLR</a> | <a href="https://arxiv.org/abs/2409.05800">arXiv</a> | <a href="https://neurips.cc/virtual/2024/workshop/84741#collapse-sl-109173">Talk (D. Krueger)</a>  <!-- Links -->
  </div>
</div>
---

---
<div style="display: flex;">
  <!-- Image on the left -->
  <img src="/images/sparsity_custom.png" alt="Description" style="width: 250px; height: 150;">

  <!-- Content on the right -->
  <div style="margin-left: 30px;">
    <h3>Sparse, interpretable ANNs for spectroscopic data</h3>  <!-- Title -->
    <p>We study custom loss penalization for MLP that leads to interpretable and spectroscopically relevant weights in the first layer.</p>  <!-- Description -->
    <a href="https://github.com/JVrabel/custom_loss_sparsity">Code</a>  <!-- Links -->
  </div>
</div>
---
<div style="display: flex;">
  <!-- Image on the left -->
  <img src="/images/double_descent.png" alt="Description" style="width: 250px; height: 150;">

  <!-- Content on the right -->
  <div style="margin-left: 30px;">
    <h3>Lottery tickets vs. double descent</h3>  <!-- Title -->
    <p>In this solo project I study intrinsic limitations of lottery ticket performances that depends on the initial effective complexity. </p>  <!-- Description -->

  </div>
</div>
---
<div style="display: flex;">
  <!-- Image on the left -->
  <img src="/images/weight_initialization.png" alt="Description" style="width: 250px; height: 150;">

  <!-- Content on the right -->
  <div style="margin-left: 30px;">
    <h3>Weight initialization with simulated spectra</h3>  <!-- Title -->
    <p>We initialize MLP weights for the first layer with simulated pure-element spectra and mixtures to guide the model towards physics-relevant solutions.</p>  <!-- Description -->
  </div>
</div>
---
**Selected past projects**

---
<div style="display: flex;">
  <!-- Image on the left -->
  <img src="/images/spectra_transfer.png" alt="Description" style="width: 250px; height: 150;">

  <!-- Content on the right -->
  <div style="margin-left: 30px;">
    <h3>Spectral library transfer between two LIBS systems</h3>  <!-- Title -->
    <p>We utilized a composed model (VAE+MLP) to transfer spectra between two distinct instruments.</p>  <!-- Description -->
    <a href="https://doi.org/10.1039/D2JA00406B">Paper</a> | <a href="https://github.com/LIBS-ML-team/libs-transfer-library">Code</a>  <!-- Links -->
  </div>
</div>
---