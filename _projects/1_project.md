---
layout: page
title: Machine learning for quantum physics
description: Learning compact representations of interacting electrons
img: assets/img/MLforPhysics.jpg
importance: 1
category: research
---

Calculating the collective behaviour of electrons requires tracking an enormous amount of information. My work asks how much of that information is essential, and how machine learning can uncover representations that make many-body calculations more efficient and physically interpretable. This connects the study of magnetism and superconductivity with the development of electronic structure methods.

## Learning the flow of electronic interactions

The functional renormalization group follows how effective interactions change as an energy or temperature scale is lowered. In our **Physical Review Letters (2022)** study of the two-dimensional Hubbard model, we used neural ordinary differential equations to learn this evolution in a compact latent space. The reduced description captured distinct magnetic and superconducting regimes, while an independent analysis of the dynamics supported the existence of a small number of important modes.

This was a demonstration of compression for a specific many-body problem, opening a route to more tractable representations of the interaction vertex: the object that describes how pairs of electrons scatter.

[Deep Learning the Functional Renormalization Group](https://doi.org/10.1103/PhysRevLett.129.136402) · *Physical Review Letters* **129**, 136402 (2022).

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/architecture.jpg" alt="Neural-network architecture for compressing functional renormalization group flows" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  The neural-network architecture used to learn a compact description of the renormalization group flow in our 2022 study.
</div>

## Interpretable compression

Our follow-up work compared principal component analysis with nonlinear autoencoders for representing the two-particle vertex. In the systems studied, a small set of principal components reconstructed the vertex across different regimes and generalized better beyond the training data than the autoencoders. The comparison also exposed differences between the fluctuations associated with ferromagnetism, antiferromagnetism, and superconductivity. It illustrates why physical insight and generalization are as important as compression alone.

[Machine learning-based compression of quantum many body physics](https://doi.org/10.1088/2632-2153/ad9f20) · *Machine Learning: Science and Technology* **5**, 045076 (2024).

## Neural networks for density functionals

In **Physical Review Research (2025)**, we extended this approach to density functional theory. We developed neural-network representations of orbital-dependent exchange-correlation functionals that respect spatial symmetries and allow their derivatives to be evaluated through automatic differentiation. Tests on molecular datasets demonstrated how orbital dependence associated with the kinetic energy density can be removed while retaining transferability across the systems examined. This provides a route toward simpler calculations of potentials, forces, and response functions.

[Neural network distillation of orbital dependent density functional theory](https://doi.org/10.1103/PhysRevResearch.7.023113) · *Physical Review Research* **7**, 023113 (2025).

The early renormalization-group work formed part of my Marie Curie **BITMAP** fellowship. An accessible account is available from the [Simons Foundation](https://www.simonsfoundation.org/2022/09/26/artificial-intelligence-reduces-a-100000-equation-quantum-physics-problem-to-only-four-equations/).

[All publications]({{ '/publications/' | relative_url }}) · [Research overview]({{ '/projects/' | relative_url }})
