# # Scaling Test-time Compute for LLM Agents
# LLM 智能体的测试计算扩展

发布时间：2025年06月15日

`Agent` `人工智能`

> Scaling Test-time Compute for LLM Agents

# 摘要

> 测试时间计算的扩展显著提升了大型语言模型（LLMs）的推理能力。本研究首次系统性地探索了将测试时间缩放方法应用于语言代理，并深入研究了其对代理有效性提升的程度。具体而言，我们探讨了以下策略：(1) 并行采样算法；(2) 串行修订策略；(3) 验证器和合并方法；(4) 多样化展开策略。通过仔细分析和消融不同设计策略对语言代理的影响，我们得出以下结论：1. 测试时间计算的扩展能够显著提升代理的性能。2. 知道何时进行反思对智能体至关重要。3. 在多种验证和结果合并方法中，基于列表的方法表现最佳。4. 增加多样化展开对智能体的任务性能产生显著的积极影响。

> Scaling test time compute has shown remarkable success in improving the reasoning abilities of large language models (LLMs). In this work, we conduct the first systematic exploration of applying test-time scaling methods to language agents and investigate the extent to which it improves their effectiveness. Specifically, we explore different test-time scaling strategies, including: (1) parallel sampling algorithms; (2) sequential revision strategies; (3) verifiers and merging methods; (4)strategies for diversifying rollouts.We carefully analyze and ablate the impact of different design strategies on applying test-time scaling on language agents, and have follow findings: 1. Scaling test time compute could improve the performance of agents. 2. Knowing when to reflect is important for agents. 3. Among different verification and result merging approaches, the list-wise method performs best. 4. Increasing diversified rollouts exerts a positive effect on the agent's task performance.

[Arxiv](https://arxiv.org/abs/2506.12928)