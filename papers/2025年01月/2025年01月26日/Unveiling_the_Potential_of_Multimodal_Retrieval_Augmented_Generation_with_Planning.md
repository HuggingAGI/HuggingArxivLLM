# 探索多模态检索增强生成与规划的无限可能

发布时间：2025年01月26日

`RAG

理由：该论文主要讨论了多模态检索增强生成（MRAG）系统的改进，提出了多模态检索增强生成规划（MRAG Planning）这一新任务，并开发了CogPlanner框架来优化多模态大型语言模型（MLLMs）的性能。这些内容与检索增强生成（RAG）密切相关，因此应归类为RAG。` `人工智能` `信息检索`

> Unveiling the Potential of Multimodal Retrieval Augmented Generation with Planning

# 摘要

> 多模态检索增强生成（MRAG）系统在提升多模态大型语言模型（MLLMs）方面潜力巨大，但其依赖的单步检索方法过于僵化，难以应对需要自适应信息获取和查询优化的复杂场景。为此，我们提出了多模态检索增强生成规划（MRAG Planning）这一新任务，旨在以最小计算开销优化MLLM性能。我们开发了CogPlanner，一个受人类认知启发的多功能框架，能够迭代优化查询并灵活选择检索策略，支持并行与顺序建模。为全面评估MRAG Planning，我们推出了CogBench基准，专为此任务设计，助力轻量级CogPlanner与高效MLLMs的无缝集成。实验证明，CogPlanner在最小计算开销下显著超越了现有MRAG基线，实现了准确性与效率的双重提升。

> Multimodal Retrieval Augmented Generation (MRAG) systems, while promising for enhancing Multimodal Large Language Models (MLLMs), often rely on rigid, single-step retrieval methods. This limitation hinders their ability to effectively address real-world scenarios that demand adaptive information acquisition and query refinement. To overcome this, we introduce the novel task of Multimodal Retrieval Augmented Generation Planning (MRAG Planning), focusing on optimizing MLLM performance while minimizing computational overhead. We present CogPlanner, a versatile framework inspired by human cognitive processes. CogPlanner iteratively refines queries and selects retrieval strategies, enabling both parallel and sequential modeling approaches. To rigorously evaluate MRAG Planning, we introduce CogBench, a new benchmark specifically designed for this task. CogBench facilitates the integration of lightweight CogPlanner with resource-efficient MLLMs. Our experimental findings demonstrate that CogPlanner surpasses existing MRAG baselines, achieving significant improvements in both accuracy and efficiency with minimal computational overhead.

[Arxiv](https://arxiv.org/abs/2501.15470)