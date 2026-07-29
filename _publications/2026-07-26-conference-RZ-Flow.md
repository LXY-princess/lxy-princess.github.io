---
title: "RZ-Flow: Readout-Zone and Feedforward-Aware Compilation for Dynamic Zoned Neutral-Atom Quantum Computers"
collection: publications
category: conferences
permalink: /publication/2026-07-26-conference-RZ-Flow
excerpt: 'Keywords: Quantum compilation, zoned neutral-atom architectures, feedforward-aware scheduling, readout-aware compilation'
date: 2026-07-26
venue: 'IEEE/ACM International Conference on Computer-Aided Design (ICCAD''26)'

citation: 'Y. Peng*, <u><b>X. Li*</b></u>, Y. Zhou, S. Niu, H. Wang, B. Yuan, and Y. Wang, Waiting for proceedings'
---

Abstract: Dynamic zoned neutral-atom quantum computers increasingly support mid-circuit readout, ancilla reuse, and real-time feedforward, turning readout from a terminal I/O step into a recurring, capacity-constrained shared architectural service. Existing zoned neutral-atom compilers, however, remain largely movement-centric and do not explicitly manage readout contention or hide feedback latency, leaving substantial exposed feedforward stall on the execution critical path. We present RZ-Flow, a readout-zone and feedforward-aware compiler for dynamic zoned neutral-atom systems with AOD-constrained transport and finite readout capacity. RZ-Flow addresses this bottleneck through three coordinated mechanisms. It first extracts measurement frontiers to identify work that is truly feedforward-dependent and work that can be released early. It then reserves scarce readout slots and pre-stages soon-to-be-measured qubits near readout. Finally, it overlaps imaging and decoding with legally independent quantum work to reduce exposed feedforward stall. Across 865 dynamic benchmark instances, RZ-Flow improves the makespan by 1.24×, reduces exposed feedforward stall by 58.1%, and improves expected fidelity proxy by 1.05% over Barrier-Greedy. Even against the per-instance strongest-baseline envelope, it retains a 1.01× makespan speedup and a 6.8% stall reduction with modest compile-time overhead. These results establish readout-aware compilation as a distinct and increasingly critical systems layer for scalable dynamic neutral-atom computing.
