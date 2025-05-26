# 强化问答智能体：极简策略梯度优化方法

发布时间：2025年05月20日

`RAG` `问答系统` `信息检索`

> Reinforcing Question Answering Agents with Minimalist Policy Gradient Optimization

# 摘要

> 大型语言模型（LLMs）展现了非凡的多功能性，但在问答（QA）任务中，由于缺乏事实知识，幻觉问题仍是其应用的主要障碍。检索增强生成通过整合外部知识缓解了这些问题，但现有方法严重依赖于上下文学习，其性能受限于LLMs的基本推理能力。本文提出了一种针对复杂问答的多跳联合智能系统Mujica，包括一个将问题分解为子问题有向无环图的规划器，以及一个通过检索和推理解决问题的工作者。此外，我们引入了MyGO（极简策略梯度优化），一种新型强化学习方法，通过从渐近最优策略中采样轨迹，用最大似然估计（MLE）替代传统策略梯度更新。MyGO消除了对梯度缩放和参考模型的需求，确保了稳定和高效的训练。跨多数据集的实证结果表明，Mujica-MyGO有效提升了多种LLMs的多跳问答性能，为复杂问答任务提供了一种可扩展且资源高效的解决方案。

> Large Language Models (LLMs) have demonstrated remarkable versatility, due to the lack of factual knowledge, their application to Question Answering (QA) tasks remains hindered by hallucination.
  While Retrieval-Augmented Generation mitigates these issues by integrating external knowledge, existing approaches rely heavily on in-context learning, whose performance is constrained by the fundamental reasoning capabilities of LLMs.
  In this paper, we propose Mujica, a Multi-hop Joint Intelligence for Complex Question Answering, comprising a planner that decomposes questions into a directed acyclic graph of subquestions and a worker that resolves questions via retrieval and reasoning. Additionally, we introduce MyGO (Minimalist policy Gradient Optimization), a novel reinforcement learning method that replaces traditional policy gradient updates with Maximum Likelihood Estimation (MLE) by sampling trajectories from an asymptotically optimal policy. MyGO eliminates the need for gradient rescaling and reference models, ensuring stable and efficient training.
  Empirical results across multiple datasets demonstrate the effectiveness of Mujica-MyGO in enhancing multi-hop QA performance for various LLMs, offering a scalable and resource-efficient solution for complex QA tasks.

[Arxiv](https://arxiv.org/abs/2505.17086)