# AirRAG: 基于树搜索激活检索增强生成的内在推理

发布时间：2025年01月17日

`RAG

理由：这篇论文主要讨论了RAG（检索增强生成）的改进方法，提出了一种名为AirRAG的新思维模式，通过蒙特卡洛树搜索（MCTS）扩展任务解决方案空间，并设计了五种基本推理动作。论文的核心内容围绕RAG的优化和应用展开，因此应归类为RAG。` `人工智能` `问答系统`

> AirRAG: Activating Intrinsic Reasoning for Retrieval Augmented Generation via Tree-based Search

# 摘要

> 大型语言模型（LLMs）的自主决策能力在推理任务中表现卓越。尽管迭代或递归的检索增强生成（RAG）取得了成功，但在复杂任务中，它们往往局限于单一解决方案空间。本文提出了一种新颖的RAG思维模式——AirRAG，它将系统分析与高效推理动作结合，通过蒙特卡洛树搜索（MCTS）显著激活内在推理能力，并扩展任务解决方案空间。具体而言，我们设计了五种基本推理动作，并通过MCTS将其扩展为广泛的树状推理空间。扩展过程还利用自一致性验证探索潜在推理路径，并实现推理扩展。此外，计算最优策略被用于对关键动作进行更多推理计算，以进一步提升性能。实验结果表明，AirRAG在复杂QA数据集上表现出显著的性能提升。此外，AirRAG灵活轻量，易于与其他先进技术集成。

> Leveraging the autonomous decision-making capabilities of large language models (LLMs) demonstrates superior performance in reasoning tasks. Despite the successes of iterative or recursive retrieval-augmented generation (RAG), they often are trapped in a single solution space when confronted with complex tasks. In this paper, we propose a novel thinking pattern in RAG which integrates system analysis with efficient reasoning actions, significantly activating intrinsic reasoning capabilities and expanding the solution space of specific tasks via Monte Carlo Tree Search (MCTS), dubbed AirRAG. Specifically, our approach designs five fundamental reasoning actions that are expanded to a wide tree-based reasoning spaces using MCTS. The extension also uses self-consistency verification to explore potential reasoning paths and implement inference scaling. In addition, computationally optimal strategies are used to apply more inference computation to key actions to achieve further performance improvements. Experimental results demonstrate the effectiveness of AirRAG through considerable performance gains over complex QA datasets. Furthermore, AirRAG is flexible and lightweight, making it easy to integrate with other advanced technologies.

[Arxiv](https://arxiv.org/abs/2501.10053)