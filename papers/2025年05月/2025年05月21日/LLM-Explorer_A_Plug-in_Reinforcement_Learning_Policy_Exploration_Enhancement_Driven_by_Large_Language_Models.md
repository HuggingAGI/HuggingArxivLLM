# LLM-Explorer：由大型语言模型驱动的强化学习策略探索增强插件工具

发布时间：2025年05月21日

`LLM应用

摘要内容主要探讨了如何将大型语言模型（LLMs）应用于强化学习（RL）中的策略探索问题，设计了一个名为LLM-Explorer的工具来增强RL中的策略探索。因此，这篇论文属于LLM应用类别。` `游戏AI` `机器人`

> LLM-Explorer: A Plug-in Reinforcement Learning Policy Exploration Enhancement Driven by Large Language Models

# 摘要

> 策略探索在强化学习（RL）中至关重要，现有的方法包括贪婪策略、高斯过程等。然而，这些方法采用预设的随机过程，并不加区分地应用于各种RL任务，未考虑影响策略探索的任务特定特征。此外，在RL训练过程中，这些随机过程的演化是刚性的，通常仅包含方差的衰减，无法根据智能体的实时学习状态灵活调整。受到大型语言模型（LLMs）分析和推理能力的启发，我们设计了LLM-Explorer，利用LLMs自适应生成任务特定的探索策略，从而增强RL中的策略探索。在我们的设计中，我们在给定任务的RL训练过程中采样智能体的学习轨迹，并提示LLM分析智能体当前的策略学习状态，然后生成未来策略探索的概率分布。通过定期更新概率分布，我们推导出专门针对特定任务且动态调整的随机过程，以适应学习过程。我们的设计是一个兼容多种广泛应用的RL算法的插件模块，包括DQN系列、DDPG、TD3以及它们的任何可能变体。通过在Atari和MuJoCo基准上的广泛实验，我们展示了LLM-Explorer增强RL策略探索的能力，平均性能提升高达37.27%。我们的代码在https://anonymous.4open.science/r/LLM-Explorer-19BE开源，以确保可重复性。

> Policy exploration is critical in reinforcement learning (RL), where existing approaches include greedy, Gaussian process, etc. However, these approaches utilize preset stochastic processes and are indiscriminately applied in all kinds of RL tasks without considering task-specific features that influence policy exploration. Moreover, during RL training, the evolution of such stochastic processes is rigid, which typically only incorporates a decay in the variance, failing to adjust flexibly according to the agent's real-time learning status. Inspired by the analyzing and reasoning capability of large language models (LLMs), we design LLM-Explorer to adaptively generate task-specific exploration strategies with LLMs, enhancing the policy exploration in RL. In our design, we sample the learning trajectory of the agent during the RL training in a given task and prompt the LLM to analyze the agent's current policy learning status and then generate a probability distribution for future policy exploration. Updating the probability distribution periodically, we derive a stochastic process specialized for the particular task and dynamically adjusted to adapt to the learning process. Our design is a plug-in module compatible with various widely applied RL algorithms, including the DQN series, DDPG, TD3, and any possible variants developed based on them. Through extensive experiments on the Atari and MuJoCo benchmarks, we demonstrate LLM-Explorer's capability to enhance RL policy exploration, achieving an average performance improvement up to 37.27%. Our code is open-source at https://anonymous.4open.science/r/LLM-Explorer-19BE for reproducibility.

[Arxiv](https://arxiv.org/abs/2505.15293)