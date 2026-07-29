---
title: "Does Scaling Up Quantum Circuits Always Help? You May Need FALCON: A Fast Latency‑Aware Hypergraph Compiler for Large-Scale Variational Quantum Circuits"
collection: publications
category: conferences
permalink: /publication/2026-07-26-conference-falcon
excerpt: 'Keywords: Variational quantum circuits, quantum compilation, hardware-aware optimization, latency-aware scheduling, hypergraph neural networks, circuit pruning'
date: 2026-07-26
venue: 'IEEE/ACM International Conference on Computer-Aided Design (ICCAD'26)'

citation: 'Y. Peng, <u><b>X. Li</b></u>, Y. Zhou, SYC. Chen, H. Tseng, KC. Chen, S. Niu, Z. Liang, and Y. Wang, Waiting for proceedings'
---

Abstract: Scaling variational quantum circuits (VQCs) naively doubles the training cost: more parameters require more repeated circuit executions for gradient estimation, and deeper circuits incur higher post-mapping latency on connectivity-limited hardware; barren plateaus can further amplify the measurement demand. This paper asks a systems question: can a compiler decide, before training, which parts of a large VQC are actually worth paying for? We present FALCON, a compile-once, latency-aware compiler that learns a compact, hardware-friendly circuit template before optimization. FALCON models a VQC as a spatiotemporal hypergraph, uses a lightweight hypergraph neural network (HGNN) to score gate slots, refines the candidate set with one-shot saliency pruning, and then applies Clifford-oriented prune and rewrite rules to reduce both trainable parameters and the mapped two-qubit critical path. Unlike prior work that reports only logical-level pruning, we evaluate FALCON with finite-shot, end-to-end metrics, shots-to-accuracy, executions-to-accuracy, and time-to-accuracy—and we further report post-mapping results on Grid, Heavy-hex, and LNN topologies. Across Heisenberg/TFIM and molecular workloads, FALCON achieves up to 10.2× parameter reduction and up to 4.0× end-to-end speedup at matched accuracy, while preserving chemical accuracy within 4.97×10−6 Ha on seven molecules. We further show that compiler overhead is dominated by qSNIP-gradient evaluation and hypergraph construction, and that warm-start weight reuse with key-based caching keeps compile latency within a practical sub-second-to-few-second regime. These results show that scaling VQCs is fundamentally a compiler and systems problem: circuit structure should be learned once at compile time to minimize time-to-accuracy end-to-end.
