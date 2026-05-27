---
title: "Deep Reinforcement Learning for Joint Power Control and Access Coordination in Energy Harvesting CIoT"
collection: publications
category: manuscripts
permalink: /publication/power-control-access
excerpt: "Deep reinforcement learning framework for joint power control and wireless access coordination in energy harvesting CIoT systems."
date: 2024-01-01
venue: "IEEE Internet of Things Journal"
paperurl: "https://ieeexplore.ieee.org/document/10601690"
citation: 'N. A. Khalek, N. Abdolkhani and W. Hamouda, "Deep Reinforcement Learning for Joint Power Control and Access Coordination in Energy Harvesting CIoT," in IEEE Internet of Things Journal, vol. 11, no. 19, pp. 30833-30846, 1 Oct.1, 2024, doi: 10.1109/JIOT.2024.3416371.'
---

## Abstract

The Internet of Things (IoT) has attracted a lot of interest owing to its various applications. Cognitive IoT (CIoT) networks utilize the cognitive radio (CR) technology to relieve spectrum congestion and boost network performance. In this context, this article proposes a novel deep reinforcement learning (DRL) approach for joint power control and channel access coordination, tailored to energy-constrained CIoT networks. Unlike the existing works, our approach considers coordination dynamics between the competing devices and adopts a realistic energy harvesting (EH) model. The goal of the CIoT transmitter is to meet the interference constraint imposed by the primary network and coordinate channel access with the other CIoT devices while optimizing its lifetime and performance. We model the joint power control and access coordination problem as a model-free Markov decision process (MDP) and introduce a novel deep Q-network (DQN) architecture. This architecture enables a CIoT transmitter to autonomously make decisions regarding EH and data transmission, while also regulating transmit power to maximize the network’s performance and lifetime. These decisions incorporate critical factors, such as channel occupancy by other devices, EH opportunities, and interference constraints without prior knowledge. Through extensive simulations we demonstrate that the proposed DQN strategy achieves faster convergence than the benchmarks, facilitating adaptive, energy-efficient, and realistic spectrum sharing in CIoT networks. Additionally, our algorithm consistently achieves higher performance in terms of average sum rate, interference ratio, and rewards compared to the benchmarks.

## Links

- [IEEE Official Publication]([https://ieeexplore.ieee.org/search/searchresult.jsp?newsearch=true&queryText=nadia%20abdolkhani](https://ieeexplore.ieee.org/document/10601690))

## BibTeX

```bibtex
@ARTICLE{10601690,
  author={Khalek, Nada Abdel and Abdolkhani, Nadia and Hamouda, Walaa},
  journal={IEEE Internet of Things Journal}, 
  title={Deep Reinforcement Learning for Joint Power Control and Access Coordination in Energy Harvesting CIoT}, 
  year={2024},
  volume={11},
  number={19},
  pages={30833-30846},
  keywords={Power control;Internet of Things;Optimization;Resource management;Performance evaluation;Radio frequency;Quality of service;Cognitive Internet of Things (CIoT);deep reinforcement learning (DRL);energy harvesting (EH)},
  doi={10.1109/JIOT.2024.3416371}}
```
