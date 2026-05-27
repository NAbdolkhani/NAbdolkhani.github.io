---
title: "Hybrid Cognitive IoT with Cooperative Caching and SWIPT: A Hierarchical Reinforcement Learning Framework"
collection: publications
category: manuscripts
permalink: /publication/hybrid-ciot-swipt
excerpt: "Hierarchical reinforcement learning framework for cooperative caching and SWIPT-enabled cognitive IoT systems."
date: 2026-02-01
venue: "IEEE Internet of Things Journal"
paperurl: "https://ieeexplore.ieee.org/document/11245504"
arxivurl: "https://arxiv.org/abs/2512.14488"
citation: 'N. Abdolkhani and W. Hamouda, "Hybrid Cognitive IoT With Cooperative Caching and SWIPT-EH: A Hierarchical Reinforcement Learning Framework," in IEEE Internet of Things Journal, vol. 13, no. 3, pp. 4277-4291, 1 Feb.1, 2026, doi: 10.1109/JIOT.2025.3632391.'
---

## Abstract

This article proposes a hierarchical deep reinforcement learning (DRL) framework based on the soft actor–critic (SAC) algorithm for hybrid underlay–overlay cognitive Internet of Things (CIoT) networks with simultaneous wireless information and power transfer (SWIPT)-energy harvesting (EH) and cooperative caching. Unlike prior hierarchical DRL approaches that focus primarily on spectrum access or power control, our work jointly optimizes EH, hybrid access coordination, power allocation, and caching in a unified framework. The joint optimization problem is formulated as a weighted-sum multiobjective task, designed to maximize throughput and cache hit ratio while simultaneously minimizing transmission delay. In the proposed model, CIoT agents jointly optimize EH and data transmission using a learnable time switching (TS) factor. They also coordinate spectrum access under hybrid overlay–underlay paradigms and make power control and cache placement decisions while considering energy, interference, and storage constraints. Specifically, in this work, cooperative caching is used to enable overlay access, while power control is used for underlay access. A novel three-level hierarchical SAC (H-SAC) agent decomposes the mixed discrete-continuous action space into modular subproblems, improving scalability and convergence over flat DRL methods. The high-level policy adjusts the TS factor, the mid-level policy manages spectrum access coordination and cache sharing, and the low-level policy decides transmit power and caching actions for both the CIoT agent and PU content. Simulation results show that the proposed H-SAC approach significantly outperforms benchmark and greedy strategies. It achieves better performance in terms of average sum rate (ASR), delay, cache hit ratio, and energy efficiency (EE), even under channel fading and uncertain conditions.


## BibTeX

```bibtex
@ARTICLE{11245504,
  author={Abdolkhani, Nadia and Hamouda, Walaa},
  journal={IEEE Internet of Things Journal}, 
  title={Hybrid Cognitive IoT With Cooperative Caching and SWIPT-EH: A Hierarchical Reinforcement Learning Framework}, 
  year={2026},
  volume={13},
  number={3},
  pages={4277-4291},
  keywords={Throughput;Optimization;Internet of Things;Power control;Cooperative caching;Resource management;Hybrid power systems;Delays;Relays;NOMA;Cognitive Internet of Things (CIoT);cooperative caching;deep reinforcement learning (DRL);energy harvesting (EH);hybrid spectrum access},
  doi={10.1109/JIOT.2025.3632391}}
```
