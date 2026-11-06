---
title: "TransCache: Opportunistic Pre-Transpilation Caching for Low-Latency Quantum-as-a-Service"
collection: publications
category: conferences
permalink: /publication/2026-09-25-conference-TransCache
excerpt: 'Keywords: Quantum cloud computing, Quantum-as-a-Service, quantum circuit transpilation, compilation caching, cache management, opportunistic prewarming'
date: 2026-09-25
venue: 'ACM Symposium on Cloud Computing Volume 2 (SoCC ’26 Vol. 2)'

citation: '<u><b>X. Li*</b></u>, Y. Peng*, S. Niu, Z. Liang, H. Wang, and Y. Wang, to appear'
---

Abstract: Quantum-as-a-Service (QaaS) is increasingly the dominant way to access quantum hardware, yet its end-to-end (E2E) latency remains high and variable. A major contributor is device-aware transpilation, which is executed on the request critical path and is a repeatable source of delay. Existing acceleration approaches either keep backend-specific transpilation on-path, or cache artifacts without (i) explicit capacity governance or (ii) safeguards against routine calibration and topology drift, limiting practical E2E gains. To tackle these problems, we propose TransCache, a backend-aware, opportunistic pre-transpilation caching architecture for latency-sensitive QaaS. TransCache moves transpilation off the critical path by forecasting near-term circuit–backend pairs and pre-transpiling them during idle cycles. To bound memory while avoiding stale reuse, TransCache combines time-to-live (TTL) pruning with a freshness- and payoff-aware eviction score that prioritizes high-value entries. Reuse is governed by epoch-aware keys so that the cache remains adaptive to hardware drift. Implemented on Qiskit Runtime and two IBM devices, TransCache consistently shrinks E2E latency in our evaluation, approaching the transpile-amortized bound. Evaluated against existing cache-based accelerators across representative circuit benchmarks, TransCache delivers approximately 2.2×–2.4× workload-scale E2E speedup relative to full recompilation (up to approximately 20× for repeated identical invocations), while improving the latency–capacity trade-off and lowering peak resident set size (RSS). These results suggest that opportunistic prewarming with calibration-aware cache governance can make transpilation layer reuse practical for latency-sensitive QaaS workloads.
