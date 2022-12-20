---
title: "Celebrating Robustness in Efficient Off-Policy Meta-Reinforcement Learning"
collection: publications
permalink: /publication/CRL
excerpt: 'Deep reinforcement learning algorithms can enable agents to learn policies for complex tasks without expert knowledge. However, the learned policies are typically specialized to one specific task and can not generalize to new tasks. While meta-reinforcement learning (meta-RL) algorithms can enable agents to solve new tasks based on prior experience, most of them build on on-policy reinforcement learning algorithms which require large amounts of samples during meta-training and do not consider task-specific features across different tasks and thus make it very difficult to train an agent with high performance. To address these challenges, in this paper, we propose an off-policy meta-RL algorithm abbreviated as CRL (Celebrating Robustness Learning) that disentangles task-specific policy parameters by an adapter network to shared low-level parameters, learns a probabilistic latent space to extract universal information across different tasks and perform temporal-extended exploration. Our approach outperforms baseline methods both in sample efficiency and asymptotic performance on several meta-RL benchmarks.'
date: 2022-07-22
venue: 'IEEE RCAR'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9872291'
citation: 'Ziyi Liu, Zongyuan Li, Qianqian Cao, Yuan Wan, Xian Guo, 2022 in RCAR.'
---

[Download paper here](https://ieeexplore.ieee.org/abstract/document/9872291)

Abstract: Deep reinforcement learning algorithms can enable agents to learn policies for complex tasks without expert knowledge. However, the learned policies are typically specialized to one specific task and can not generalize to new tasks. While meta-reinforcement learning (meta-RL) algorithms can enable agents to solve new tasks based on prior experience, most of them build on on-policy reinforcement learning algorithms which require large amounts of samples during meta-training and do not consider task-specific features across different tasks and thus make it very difficult to train an agent with high performance. To address these challenges, in this paper, we propose an off-policy meta-RL algorithm abbreviated as CRL (Celebrating Robustness Learning) that disentangles task-specific policy parameters by an adapter network to shared low-level parameters, learns a probabilistic latent space to extract universal information across different tasks and perform temporal-extended exploration. Our approach outperforms baseline methods both in sample efficiency and asymptotic performance on several meta-RL benchmarks.


