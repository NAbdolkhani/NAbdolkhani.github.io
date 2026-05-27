---
title: "Deep Reinforcement Learning for EH-Enabled Cognitive-IoT Under Jamming Attacks"
collection: publications
category: manuscripts
permalink: /publication/eh-ciot-jamming
excerpt: "Deep reinforcement learning framework for energy harvesting-enabled cognitive IoT systems under jamming attacks."
date: 2024-12-01
venue: "IEEE Internet of Things Journal"
paperurl: "https://ieeexplore.ieee.org/document/10673973"
arxivurl: "https://arxiv.org/abs/2512.15558"
citation: 'N. Abdolkhani, N. A. Khalek and W. Hamouda, "Deep Reinforcement Learning for EH-Enabled Cognitive-IoT Under Jamming Attacks," in IEEE Internet of Things Journal, vol. 11, no. 24, pp. 40800-40813, 15 Dec.15, 2024, doi: 10.1109/JIOT.2024.3457012.'
---

## Abstract

In the evolving landscape of the Internet of Things (IoT), integrating cognitive radio (CR) has become a practical solution to address the challenge of spectrum scarcity, leading to the development of Cognitive IoT (CIoT). However, the vulnerability of radio communications makes radio jamming attacks a key concern in CIoT networks. In this article, we introduce a novel deep reinforcement learning (DRL) approach designed to optimize throughput and extend network lifetime of an energy-constrained CIoT system under jamming attacks. This DRL framework equips a CIoT device with the autonomy to manage energy harvesting (EH) and data transmission, while also regulating its transmit power to respect spectrum-sharing constraints. We formulate the optimization problem under various constraints, and we model the CIoT device’s interactions within the channel as a model-free Markov decision process (MDP). The MDP serves as a foundation to develop a double deep Q-network (DDQN), designed to help the CIoT agent learn the optimal communication policy to navigate challenges, such as dynamic channel occupancy, jamming attacks, and channel fading while achieving its goal. Additionally, we introduce a variant of the upper confidence bound (UCB) algorithm, named UCB interference-aware (UCB-IA), which enhances the CIoT network’s ability to efficiently navigate jamming attacks within the channel. The proposed DRL algorithm does not rely on prior knowledge and uses locally observable information, such as channel occupancy, jamming activity, channel gain, and energy arrival to make decisions. Extensive simulations prove that our proposed DRL algorithm that utilizes the UCB-IA strategy surpasses existing benchmarks, allowing for a more adaptive, energy-efficient, and secure spectrum sharing in CIoT networks.

## Links

- [IEEE Official Publication](https://ieeexplore.ieee.org/document/10673973)
- [arXiv Preprint](https://arxiv.org/abs/2512.15558)

## BibTeX

```bibtex
@ARTICLE{10673973,
  author={Abdolkhani, Nadia and Khalek, Nada Abdel and Hamouda, Walaa},
  journal={IEEE Internet of Things Journal}, 
  title={Deep Reinforcement Learning for EH-Enabled Cognitive-IoT Under Jamming Attacks}, 
  year={2024},
  volume={11},
  number={24},
  pages={40800-40813},
  keywords={Jamming;Internet of Things;Heuristic algorithms;Power control;Game theory;Throughput;Radio frequency;Cognitive Internet of Things (CIoT);deep reinforcement learning (DRL);energy harvesting (EH);jamming attacks;upper confidence bound (UCB)},
  doi={10.1109/JIOT.2024.3457012}}
```
