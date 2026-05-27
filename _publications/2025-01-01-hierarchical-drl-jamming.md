---
title: "Hierarchical Deep Reinforcement Learning for Robust Access in Cognitive IoT Networks under Smart Jamming Attacks"
collection: publications
category: conferences
permalink: /publication/hierarchical-drl-jamming
excerpt: "Hierarchical deep reinforcement learning for robust wireless access under smart jamming attacks."
date: 2025-12-08
venue: "IEEE GLOBECOM 2025"
paperurl: "https://ieeexplore.ieee.org/document/11431821"
arxivurl: "https://arxiv.org/abs/2512.14013"
citation: 'N. Abdolkhani and W. Hamouda, "Hierarchical Deep Reinforcement Learning for Robust Access in Cognitive IoT Networks under Smart Jamming Attacks," GLOBECOM 2025 - 2025 IEEE Global Communications Conference, Taipei, Taiwan, 2025, pp. 3164-3169, doi: 10.1109/GLOBECOM59602.2025.11431821.'
---

## Abstract

In this paper, we address the challenge of dynamic spectrum access in a cognitive Internet of Things (CIoT) network where a secondary user (SU) operates under both energy constraints and adversarial interference from a smart jammer. The SU coexists with primary users (PUs) and must ensure that its transmissions do not exceed a predefined interference threshold on licensed channels. At each time slot, the SU must jointly determine whether to transmit or harvest energy, which channel to access, and the appropriate transmit power while satisfying energy and interference constraints. Meanwhile, a smart jammer actively selects a channel to disrupt, aiming to degrade the SU’s communication performance. This setting presents a significant challenge due to its multi-level decision structure and hybrid action space, which combines both discrete and continuous decisions. To tackle this, we propose a novel Hierarchical Deep Deterministic Policy Gradient (H-DDPG) framework that decomposes the decision-making process into three levels: the high-level policy determines the mode (transmit or harvest), the mid-level policy selects the channel, and the low-level actor outputs a continuous power level. Concurrently, the jammer is modeled as a reinforcement learning agent that learns an adaptive channel jamming strategy using a discrete variant of DDPG. Simulation results show that our H-DDPG approach outperforms conventional flat reinforcement learning baselines.


## BibTeX

```bibtex
@INPROCEEDINGS{11431821,
  author={Abdolkhani, Nadia and Hamouda, Walaa},
  booktitle={GLOBECOM 2025 - 2025 IEEE Global Communications Conference}, 
  title={Hierarchical Deep Reinforcement Learning for Robust Access in Cognitive IoT Networks under Smart Jamming Attacks}, 
  year={2025},
  volume={},
  number={},
  pages={3164-3169},
  keywords={Adaptation models;Upper bound;Simulation;Decision making;Power control;Deep reinforcement learning;Internet of Things;Jamming;Interference constraints;Resilience;cognitive radio networks;spectrum sharing;smart jammer;deep reinforcement learning},
  doi={10.1109/GLOBECOM59602.2025.11431821}}
```
