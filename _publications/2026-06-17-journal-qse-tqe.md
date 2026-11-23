---
title: "Quantum Squeeze-and-Excitation Networks: Harnessing Quantum Noise for Robust Attention Mechanisms in Hybrid Architectures"
collection: publications
category: manuscripts
permalink: /publication/2026-06-17-journal-qse-tqe
excerpt: 'Keywords: Attention networks, quantum computing, quantum machine learning, quantum noise, topology'
date: 2026-06-17
venue: 'IEEE Transactions on Quantum Engineering'
key: qse-tqe
venue_short: "IEEE TQE"
authors:
  - "Yifeng Peng"
  - "Xinyi Li"
  - "Ying Wang"
pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11578346"
paperurl: "https://ieeexplore.ieee.org/document/11578346"
doi: "10.1109/TQE.2026.3707472"
citation: 'Y. Peng, <u><b>X. Li</b></u>, and Y. Wang, "Quantum Squeeze-and-Excitation Networks: Harnessing Quantum Noise for Robust Attention Mechanisms in Hybrid Architectures," in IEEE Transactions on Quantum Engineering, vol. 7, 2026, Art no. 3104427, doi: 10.1109/TQE.2026.3707472.'
---

Abstract: By simulating the selective focus characteristics of human visual attention, the attention network has greatly improved the model's ability to capture key features, promoting significant progress in natural language processing, computer vision, and other fields. As a typical attention mechanism, the squeeze-and-excitation (SE) module finely adjusts the feature representation of the neural network by reweighting the features between channels, further enhancing the performance and generalization ability of the model. In this article, we introduce quantum squeeze-and-excitation (QSE) networks, a pioneering approach that enhances the excitation module of classical SE networks using quantum computing. Our method simplifies the model's complexity and boosts performance by employing quantum amplitude coding for data encoding, significantly reducing the parameter count of fully connected layers in classical SE module. To optimize the quantum circuits within the QSE module, we explore five different controlled quantum-NOT (CNOT) gate topologies: circular, linear, star, tree, and mesh. Experimental results show that, after 100 training rounds, the accuracy of our proposed linear topology-based QSE ResNet-18 on the CIFAR-10 dataset reached 85.00% in no noise case, while the classical SE ResNet-18 was only 82.20%. Contrary to the common perception of noise as a disruptive and unavoidable challenge, we demonstrate that, through specific topology structures and a hybrid quantum-classical QSE design, quantum noise does not need to be deliberately avoided. Instead, we leverage quantum noise to enhance the robustness of QSE networks and mitigate the local optima trapping problem caused by circuit redundancy by four quantum noise models—amplitude damping, depolarizing, phase-flip, and bit-flip noise. Experimental results show that under four noise models, the QSE accuracy of the five different topological results we proposed can reach a performance of more than 85.00%. The inevitable quantum noise inherently serves as an advantage in the proposed QSE.
