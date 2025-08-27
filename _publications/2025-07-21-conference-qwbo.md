---
title: "QWBO: QAOA-Based High-Speed Weighted Black-box Hyperparameter Optimization for XGBoost in UAV Fingerprinting,"
collection: publications
category: conferences
permalink: /publication/2025-07-21-conference-qwbo
excerpt: 'Keywords: Hyperparameter Optimization, Quantum Approximate Optimization Algorithm, Secure Unmanned Aerial Vehicle Fingerprinting, XGBoost'
date: 2025-07-21
venue: '2025 IEEE International Conference on Quantum Computing and Engineering (QCE-25)'
citation: '<u><b>X. Li</b></u>, Y. Peng, and Y. Wang, Waiting for proceedings'
---

Abstract: The rapid development of Machine Learning (ML) algorithms across domains necessitates efficient Hyperparameter Optimization (HPO) to tailor models to specific tasks. Classical HPO techniques become prohibitively slow as model size and search space dimensionality grow. Quantum computing, particularly the Quantum Approximate Optimization Algorithm (QAOA), offers a principled way to explore large combinatorial spaces, but existing QAOA approaches are limited in black-box ML settings, where objective evaluations are expensive. The need for fast yet accurate HPO is most acute in security-critical applications such as Unmanned Aerial Vehicle (UAV) fingerprinting, where defenders must identify hostile drones within seconds. To address this challenge, we propose a QAOA-Based High-Speed Weighted Black-box Hyperparameter Optimization (QWBO), a generic HPO method that directly encodes discretized hyperparameters into qubits. A customized QAOA circuit imposes data-driven penalty weights, and its low-energy states decode to the optimal hyperparameter set. We evaluate QWBO on a real-world XGBoost-based UAV fingerprinting task. QWBO attains 93% classification accuracy, surpassing grid search and Bayesian optimization while requiring far less runtime. Moreover, its runtime grows sublinearly with search space size, demonstrating strong potential for rapid, large-scale HPO across diverse ML models and security domains.
