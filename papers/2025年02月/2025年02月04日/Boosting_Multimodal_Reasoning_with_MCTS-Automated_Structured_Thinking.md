# 多模态推理的飞跃：MCTS驱动的自动化结构化思维

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要讨论的是多模态大型语言模型（MLLMs）在复杂视觉推理中的应用，并提出了一种新的自动化结构化思维范式（AStar）来提升其推理能力。论文的核心在于如何通过改进模型的结构和推理方法来提高性能与效率，这属于LLM在实际应用中的优化和改进，因此应归类为LLM应用。` `人工智能` `推理系统`

> Boosting Multimodal Reasoning with MCTS-Automated Structured Thinking

# 摘要

> 多模态大型语言模型（MLLMs）在复杂视觉推理方面表现出色，但仍面临挑战。尽管近期研究尝试通过引入类似OpenAI o1的结构化思维来提升MLLMs的推理能力，但往往难以兼顾性能与效率。其核心问题在于对大量数据和搜索空间的过度依赖，导致隐式洞察提取和数据利用效率低下。为此，我们提出了AStar，一种基于蒙特卡洛树搜索（MCTS）的自动化结构化思维范式。AStar通过MCTS驱动的层次结构，从有限数据中自动提取高级认知推理模式。基于这些模式，我们设计了一个统一的推理框架，将模型的内部推理能力与外部推理指南无缝结合，实现了在最小树迭代下的高效推理。这一创新范式在性能与效率之间取得了卓越平衡。大量实验表明，AStar在MathVerse基准测试中，使用7B骨干网络达到了54.0%的准确率，超越了GPT-4o（50.2%），同时保持了显著的数据和计算效率。

> Multimodal large language models (MLLMs) exhibit impressive capabilities but still face challenges in complex visual reasoning. While recent efforts attempt to enhance MLLMs' reasoning by incorporating OpenAI o1-like structured thinking through explicit search structures or teacher-guided distillation, they often struggle to balance performance and efficiency. A critical limitation is their heavy reliance on extensive data and search spaces, resulting in low-efficiency implicit insight extraction and data utilization. To address this, we propose AStar, an Automated Structured thinking paradigm for multimodal reasoning via Monte Carlo Tree Search (MCTS). AStar automatically derives high-level cognitive reasoning patterns from limited data using MCTS-powered hierarchical structures. Building on these explicit patterns, we design a unified reasoning framework that seamlessly integrates models' internal reasoning capabilities and external reasoning guidelines, enabling efficient inference with minimal tree iterations. This novel paradigm strikes a compelling balance between performance and efficiency. Extensive experiments demonstrate AStar's effectiveness, achieving superior accuracy (54.0$\%$) on the MathVerse benchmark with a 7B backbone, surpassing GPT-4o (50.2$\%$) while maintaining substantial data and computational efficiency.

[Arxiv](https://arxiv.org/abs/2502.02339)