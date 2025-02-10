# 多智能体学习的焦点多样性优化方法

发布时间：2025年02月06日

`Agent` `人工智能` `机器学习`

> Multi-Agent Reinforcement Learning with Focal Diversity Optimization

# 摘要

> 大型语言模型 (LLMs) 的发展及其微调策略的演进重新点燃了人们对多智能体强化学习的关注。本文提出了一种名为 MARL-Focal 的焦点多样性优化多智能体强化学习方法，该方法具有三大独特优势。首先，我们设计了一个智能体融合框架，旨在促进多个基于 LLM 的智能体在处理每个 LLM 查询时协同工作，共同生成最终推理结果。其次，我们开发了一种焦点多样性优化的智能体选择算法，能够根据智能体之间的互补性，从可用智能体中精选出一个小型高效子集，以生成最优的查询输出。最后，我们创新了一种冲突解决机制，用于检测多智能体间的输出不一致，并通过奖励感知和策略自适应的推理融合方式生成最终的 MARL-Focal 结果。在五个基准测试中的全面评估显示，MARL-Focal 不仅成本效益显著，还具备强大的对抗鲁棒性。我们的多智能体融合模型相较于最佳个体 LLM 智能体，性能提升了 5.51%，并且在 TruthfulQA 基准测试中展现出了更卓越的鲁棒性。项目代码已开源，访问 https://github.com/sftekin/rl-focal 即可获取。

> The advancement of Large Language Models (LLMs) and their finetuning strategies has triggered the renewed interests in multi-agent reinforcement learning. In this paper, we introduce a focal diversity-optimized multi-agent reinforcement learning approach, coined as MARL-Focal, with three unique characteristics. First, we develop an agent-fusion framework for encouraging multiple LLM based agents to collaborate in producing the final inference output for each LLM query. Second, we develop a focal-diversity optimized agent selection algorithm that can choose a small subset of the available agents based on how well they can complement one another to generate the query output. Finally, we design a conflict-resolution method to detect output inconsistency among multiple agents and produce our MARL-Focal output through reward-aware and policy-adaptive inference fusion. Extensive evaluations on five benchmarks show that MARL-Focal is cost-efficient and adversarial-robust. Our multi-agent fusion model achieves performance improvement of 5.51\% compared to the best individual LLM-agent and offers stronger robustness over the TruthfulQA benchmark. Code is available at https://github.com/sftekin/rl-focal

[Arxiv](https://arxiv.org/abs/2502.04492)