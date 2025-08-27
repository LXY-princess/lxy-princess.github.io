---
title: "CoCo: A CBOW-Based Framework for Synergistic Vulnerability Detection in Partial and Discontinuous Logs for NextG Communications"
collection: publications
category: manuscripts
permalink: /publication/2024-10-01-journal-coco
excerpt: 'Keywords: Machine learning, Word2Vec, CBOW, NextG vulnerability detection, fuzz testing'
date: 2024-10-01
venue: 'IEEE Open Journal of the Communications Society'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10701039'
citation: 'Y. Peng, X. Li, S. Arya and Y. Wang, "CoCo: A CBOW-Based Framework for Synergistic Vulnerability Detection in Partial and Discontinuous Logs for NextG Communications," in IEEE Open Journal of the Communications Society, vol. 5, pp. 6381-6403, 2024, doi: 10.1109/OJCOMS.2024.3471709.
keywords: {Fuzzing;Security;5G mobile communication;Machine learning;Accuracy;Natural language processing;Scalability;Real-time systems;Internet of Things;Analytical models;Machine learning;Word2Vec;CBOW;NextG vulnerability detection;fuzz testing},'
---

Abstract: With the development of communication technology, protocol design, and infrastructure implementation have become more complex, bringing significant security challenges to 5G and NextG systems. Fuzz testing is widely used to detect system vulnerabilities and the health status under the condition of abnormal input. In this paper, we generate fuzz testing via the Man In The Middle Model (MITM) at various locations of the time sequence in the 5G authentication and authorization process and analyze the communication state transitions, which are recorded in the log files of fuzz testing cases. CoCo introduces a novel CBOW-based framework for synergistic vulnerability detection, addressing the challenge of partial log data and scalability in real-time environments, a significant advancement in the field of NextG communication security. CoCo can be applied to identifying the type of attacks or abnormal inputs from partial system profiling for the impacted behaviors. In particular, we show, for the first time, that by utilizing the CoCo, we can precisely detect the fuzzed layer using only a partial segment of the log file in real-time and identify the root cause of vulnerabilities with high accuracy. The results show that when we get only 40% portion of the entire log file, applying convolutional neural network (CNN) in the machine learning models can reach the Area under Curve (AUC) value of 92%. Furthermore, by strategically combining these segments, we enhanced the efficacy of vulnerability detection, demonstrating a synergistic effect where the combined impact is greater than the sum of individual parts, meanwhile reducing the time complexity by 6%.
