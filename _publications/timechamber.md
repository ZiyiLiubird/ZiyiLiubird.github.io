---
title: "TimeChamber: A Massively Parallel Large Scale Self-Play Framework"
collection: publications
permalink: /publication/timechamber
excerpt: 'TimeChamber is a large scale self-play framework running on parallel simulation. Running self-play algorithms always need lots of hardware resources, especially on 3D physically simulated environments. We provide a self-play framework that can achieve fast training and evaluation with ONLY ONE GPU.'
date: 2022-09-30
venue: 'Github'
# paperurl: 'https://github.com/inspirai/TimeChamber'
# citation: 'Huang Ziming, Ziyi Liu, Wu Yutong, Flood Sung.'
---

[Visit project page here](https://github.com/inspirai/TimeChamber)

Abstract: 

TimeChamber is a large scale self-play framework running on parallel simulation. Running self-play algorithms always need lots of hardware resources, especially on 3D physically simulated environments. We provide a self-play framework that can achieve fast training and evaluation with ONLY ONE GPU. TimeChamber is developed with the following key features:

- Parallel Simulation: TimeChamber is built within Isaac Gym. Isaac Gym is a fast GPU-based simulation platform. It supports running thousands of environments in parallel on a single GPU.For example, on one NVIDIA Laptop RTX 3070Ti GPU, TimeChamber can reach 80,000+ mean FPS by running 4,096 environments in parallel.
- Parallel Evaluation: TimeChamber can fast calculate dozens of policies' ELO rating(represent their combat power). It also supports multi-player ELO calculations by multi-elo. Inspired by Vectorization techniques for fast population-based training, we leverage the vectorized models to evaluate different policy in parallel.
- Prioritized Fictitious Self-Play Benchmark: We implement a classic PPO self-play algorithm on top of rl_games, with a prioritized player pool to avoid cycles and improve the diversity of training policy.

<div align=center>
<img src="algorithm.jpg" align="center" width="600"/>
</div> 

- **Competitive Multi-Agent Tasks**: Inspired by [OpenAI RoboSumo](https://github.com/openai/robosumo), we introduce two
  competitive multi-agent tasks(e.g.,Ant Sumo,Ant
  Battle) as examples.

Recommended citation:

@misc{InspirAI,
  author = {Huang Ziming, Ziyi Liu, Wu Yutong, Flood Sung},
  title = {TimeChamber: A Massively Parallel Large Scale Self-Play Framework},
  year = {2022},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/inspirai/TimeChamber}},
}