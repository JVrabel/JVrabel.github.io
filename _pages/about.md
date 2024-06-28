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

NEW: For the summer 2024 I am a visiting Ph.D. student at KASL $\subset$ ML group $\subset$ CBL $\subset$ University of Cambridge, working on input space mode connectivity (advised by D. Krueger).

I am a Ph.D. candidate in applied physics at [CEITEC](https://www.ceitec.eu/) in the Czech Republic. My research focuses on interpretable machine learning (ML) applied to spectroscopic data and physics-inspired learning. Lately, I am mostly interested in understanding deep learning through empirical and theoretical methods, usually grounded in physics. The main motivation is to achieve interpretable and safe ML/AI for science and general use. This includes various topics in overparametrization, sparsity and adversarial robustness of deep networks.

When I'm not busy with ML experiments, you can find me bouldering or cycling. I also enjoy hiking, playing guitar, and reading physics books from my vast collection.

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


---
**Current projects**

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