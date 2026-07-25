---
title: "Where Atom Loss Lands Matters: Decoder-Aware Risk Deposition in Neutral-Atom QEC"
collection: publications
category: conferences
permalink: /publication/2026-07-21-conference-CAST
excerpt: 'Keywords: neutral atoms, quantum error correction, atom loss, erasure decoding, compiler'
date: 2026-07-21
venue: '2026 IEEE International Conference on Quantum Computing and Engineering (QCE-26)'

citation: '<u><b>X. Li</b></u>, Y. Peng, and Y. Wang, Waiting for proceedings'
---

Abstract: Neutral-atom arrays are emerging as a leading platform for scalable quantum error correction (QEC). Qubits are routed and reused across the array, while detected loss is reported to the decoder as erasure information. Existing neutral-atom compilers optimize this movement, including routing, shuttling, and reuse, and often model loss through scalar exposure costs. Yet total exposure is an incomplete statistic for erasure-corrected QEC. It captures how much loss occurs, but not where it lands on the code, which we call its deposition. Under the same expected atom-loss budget, different deposition patterns over a code patch induce substantially different logical error rates (LER). We formalize this as decoder-aware risk deposition and present CAST, a compiler-side optimization pass that overlays a code-topology sensitivity map on a role-indexed exposure ledger and minimizes a decoder-weighted harm objective under a comparable-exposure constraint, using only local route, role, and seam-cooling actions. Across surface-code memory, physical-scale architecture models, lattice surgery, and decoder-mismatch checks, CAST lowers LER relative to topology-blind exposure minimization, improving on it in 35 of 48 physical-scale settings and by as much as 5.3x where exposure is heterogeneous and routing has slack. The largest gains occur when high exposure and high decoder sensitivity are initially misaligned, giving CAST room to redirect risk toward lower-impact code roles. CAST shows that decoder-aware atom-loss risk deposition can be optimized as a compiler-side pass in neutral-atom QEC.
