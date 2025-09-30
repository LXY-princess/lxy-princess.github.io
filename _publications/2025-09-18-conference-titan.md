---
title: "TITAN: A Trajectory-Informed Technique for Adaptive Parameter Freezing in Large-Scale VQE"
collection: publications
category: conferences
permalink: /publication/2025-09-18-conference-titan
excerpt: ''
date: 2025-09-18
venue: 'The Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025)'
citation: 'Y. Peng, <u><b>X. Li</b></u>, S. Chen, K. Zhang, and Z. Liang, Y. Wang, and Y. Du. Waiting for proceedings.'
paperurl: "https://arxiv.org/abs/2509.15193"
---

Abstract: Variational quantum Eigensolver (VQE) is a leading candidate for harnessing quantum computers to advance quantum chemistry and materials simulations, yet its
training efficiency deteriorates rapidly for large Hamiltonians. Two issues underlie
this bottleneck: (i) the no-cloning theorem imposes a linear growth in circuit evaluations with the number of parameters per gradient step; and (ii) deeper circuits
encounter barren plateaus (BPs), leading to exponentially increasing measurement
overheads. To address these challenges, here we propose a deep learning framework, dubbed TITAN, which identifies and freezes inactive parameters of a given
ansätze at initialization for a specific class of Hamiltonians, reducing the optimization overhead without sacrificing accuracy. The motivation of TITAN starts with our
empirical findings that a subset of parameters consistently has negligible influence
on training dynamics. Its design combines a theoretically grounded data construction strategy, ensuring each training example is informative and BP-resilient, with
an adaptive neural architecture that generalizes across ansätze of varying sizes.
Across benchmark transverse-field Ising models, Heisenberg models, and multiple
molecule systems up to 30 qubits, TITAN achieves up to 3× faster convergence and
40–60% fewer circuit evaluations than state-of-the-art baselines, while matching or
surpassing their estimation accuracy. By proactively trimming parameter space,
TITAN lowers hardware demands and offers a scalable path toward utilizing VQE
to advance practical quantum chemistry and materials science.
