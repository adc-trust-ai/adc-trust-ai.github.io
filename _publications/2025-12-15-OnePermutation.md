---
title: "One Permutation Is All You Need: Fast, Reliable Variable Importance and Model Stress-Testing"
collection: 'publications'
permalink: /publications/2025-12-15-OnePermutation
excerpt: 
date: 2025-12-15
venue:
paperurl:
preprinturl: https://arxiv.org/abs/2512.13892
citation: 'Dorador, A. (2025+). &quot;One Permutation Is All You Need: Fast, Reliable Variable Importance and Model Stress-Testing.&quot;'
note: 'preprint'
---

<b> Abstract </b> : 
Reliable estimation of feature contributions in machine learning models is essential for trust, transparency and regulatory compliance, especially when models are proprietary or otherwise operate as black boxes.
While permutation-based methods are a standard tool for this task, classical implementations rely on repeated random permutations, introducing computational overhead and stochastic instability.
In this paper, we show that by replacing multiple random permutations with a single, deterministic, and optimal permutation, we achieve a method that retains the core principles of permutation-based importance while being non-random, faster, and more stable.
We validate this approach across nearly 200 scenarios, including real-world household finance and credit risk applications, demonstrating improved bias-variance tradeoffs and accuracy in challenging regimes such as small sample sizes, high dimensionality, and low signal-to-noise ratios.
Finally, we introduce Systemic Variable Importance, a natural extension designed for model stress-testing that explicitly accounts for feature correlations. This framework provides a transparent way to quantify how shocks or perturbations propagate through correlated inputs, revealing dependencies that standard variable importance measures miss.
Two real-world case studies demonstrate how this metric can be used to audit models for hidden reliance on protected attributes (e.g., gender or race), enabling regulators and practitioners to assess fairness and systemic risk in a principled and computationally efficient manner.

---
