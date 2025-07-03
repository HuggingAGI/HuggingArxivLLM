# RALLY：用于智能体无人机群的基于角色自适应的LLM驱动同步导航方法

发布时间：2025年07月02日

`LLM应用` `无人机`

> RALLY: Role-Adaptive LLM-Driven Yoked Navigation for Agentic UAV Swarms

# 摘要

> 无人机群的智能控制已成为关键研究重点，要求无人机群在有效导航的同时避开障碍物，并对多个任务目标实现连续覆盖。传统多智能体强化学习（MARL）方法虽具备动态适应性，但受限于数值通信语义鸿沟和 rigidity 的同质化角色结构，导致泛化能力差且任务扩展性有限。近期基于大型语言模型（LLM）的控制框架展示了强大的语义推理能力，但因缺乏在线学习且过度依赖静态先验，难以有效探索，导致个体潜力和整体性能下降。为解决这些问题，我们提出了一种基于角色自适应的LLM驱动协同导航算法RALLY。首先，我们开发了一个LLM驱动的语义决策框架，利用结构化自然语言实现高效的语义通信和协作推理。随后，引入动态角色异质性机制，实现自适应角色切换和个性化决策。此外，提出基于角色值混合网络（RMIX）的分配策略，将LLM的离线先验与MARL的在线策略相结合，实现角色选择策略的半离线训练。在多智能体粒子环境（MPE）和软件在环（SITL）平台上的实验表明，RALLY在任务覆盖、收敛速度和泛化能力方面均优于传统方法，突显了其在多智能体无人机系统中协同导航的潜力。

> Intelligent control of Unmanned Aerial Vehicles (UAVs) swarms has emerged as a critical research focus, and it typically requires the swarm to navigate effectively while avoiding obstacles and achieving continuous coverage over multiple mission targets. Although traditional Multi-Agent Reinforcement Learning (MARL) approaches offer dynamic adaptability, they are hindered by the semantic gap in numerical communication and the rigidity of homogeneous role structures, resulting in poor generalization and limited task scalability. Recent advances in Large Language Model (LLM)-based control frameworks demonstrate strong semantic reasoning capabilities by leveraging extensive prior knowledge. However, due to the lack of online learning and over-reliance on static priors, these works often struggle with effective exploration, leading to reduced individual potential and overall system performance. To address these limitations, we propose a Role-Adaptive LLM-Driven Yoked navigation algorithm RALLY. Specifically, we first develop an LLM-driven semantic decision framework that uses structured natural language for efficient semantic communication and collaborative reasoning. Afterward, we introduce a dynamic role-heterogeneity mechanism for adaptive role switching and personalized decision-making. Furthermore, we propose a Role-value Mixing Network (RMIX)-based assignment strategy that integrates LLM offline priors with MARL online policies to enable semi-offline training of role selection strategies. Experiments in the Multi-Agent Particle Environment (MPE) environment and a Software-In-The-Loop (SITL) platform demonstrate that RALLY outperforms conventional approaches in terms of task coverage, convergence speed, and generalization, highlighting its strong potential for collaborative navigation in agentic multi-UAV systems.

[Arxiv](https://arxiv.org/abs/2507.01378)