---
title: "HCVS-Net: Hybrid Continuous-Variable Squeezing Network"
collection: publications
category: conferences
permalink: /publication/2025-07-21-conference-hcvs
excerpt: 'Keywords: Continuous-Variable Quantum Computing, Hybrid Quantum-Classical Systems, Robust Feature Extraction, Squeezing Operations'
date: 2025-07-21
venue: '2025 IEEE International Conference on Quantum Computing and Engineering (QCE-25)'
citation: 'X. Li, Y. Peng, J. Chen, and Y. Wang, Waiting for proceedings'
---

Abstract: Recent advances in quantum-inspired machine learning have highlighted the potential of using non-classical effects to enhance feature extraction and improve robustness. In particular, continuous-variable (CV) systems on photonic platforms offer operations such as single-mode and two-mode squeezing that naturally encode quantum correlations. Motivated by the need for increasingly resilient and expressive deep learning architectures, we propose a novel Hybrid Continuous-Variable Squeezing Network (HCVS-Net) that unifies these quantum-inspired CV operations with classical convolutional neural networks (CNNs) by skip-connection. Specifically, a conventional CNN first extracts preliminary features, which are subsequently embedded into CV modes undergoing controllable squeezing gates, emulating spontaneous parametric down-conversion. This process yields enriched feature representations through quadrature measurements. Our experimental results on MNIST confirm that HCVS-Net surpasses purely classical baselines, achieving both competitive accuracy and heightened resilience to brightness distortions. Under low brightness conditions of 0.1, the accuracy is about 3% higher than that of pure CNN. Furthermore, the entire model is end-to-end differentiable, allowing both classical parameters and quantum-like squeezing parameters to be trained jointly via backpropagation. 
