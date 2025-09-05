# # 学会何时规划：面向LLM智能体的测试时计算资源高效分配

发布时间：2025年09月03日

`Agent` `基础理论`

> Learning When to Plan: Efficiently Allocating Test-Time Compute for LLM Agents

# 摘要

> 通过强化学习（RL）训练大型语言模型（LLMs）进行推理，能显著增强其问题解决能力。在智能体场景中，现有方法（如ReAct）会提示LLMs在每次行动前进行显式规划；但我们发现，始终规划不仅计算成本高昂，还会降低长程任务的性能，而完全不规划则会进一步限制性能。为解决这一问题，我们提出了一个概念框架，为LLM智能体构建动态规划的形式化模型，使其能够灵活决定何时为规划分配测试时计算资源。我们设计了一个简洁的两阶段训练流程：（1）在多样化合成数据上进行监督微调，引导模型掌握动态规划基础；（2）通过强化学习在长程环境中进一步优化该能力。在Crafter环境中的实验显示，采用该方法训练的动态规划智能体样本效率更高，且能稳定达成更复杂的目标。此外，我们还发现这些智能体可通过人类编写的计划进行有效调控，其表现甚至超越了自主能力。据我们所知，本研究首次探索了在序贯决策任务中训练LLM智能体实现动态测试时计算资源分配，为构建更高效、自适应且可控的智能体系统奠定了基础。

> Training large language models (LLMs) to reason via reinforcement learning (RL) significantly improves their problem-solving capabilities. In agentic settings, existing methods like ReAct prompt LLMs to explicitly plan before every action; however, we demonstrate that always planning is computationally expensive and degrades performance on long-horizon tasks, while never planning further limits performance. To address this, we introduce a conceptual framework formalizing dynamic planning for LLM agents, enabling them to flexibly decide when to allocate test-time compute for planning. We propose a simple two-stage training pipeline: (1) supervised fine-tuning on diverse synthetic data to prime models for dynamic planning, and (2) RL to refine this capability in long-horizon environments. Experiments on the Crafter environment show that dynamic planning agents trained with this approach are more sample-efficient and consistently achieve more complex objectives. Additionally, we demonstrate that these agents can be effectively steered by human-written plans, surpassing their independent capabilities. To our knowledge, this work is the first to explore training LLM agents for dynamic test-time compute allocation in sequential decision-making tasks, paving the way for more efficient, adaptive, and controllable agentic systems.

[Arxiv](https://arxiv.org/abs/2509.03581)