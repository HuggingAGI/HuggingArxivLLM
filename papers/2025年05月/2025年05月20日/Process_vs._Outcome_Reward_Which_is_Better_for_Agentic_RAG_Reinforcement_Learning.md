# 过程与结果奖励：哪个更适合代理式 RAG 强化学习？

发布时间：2025年05月20日

`RAG` `信息检索`

> Process vs. Outcome Reward: Which is Better for Agentic RAG Reinforcement Learning

# 摘要

> 检索增强生成（RAG）通过整合外部知识和最新信息，显著提升了大型语言模型（LLMs）的文本生成能力。然而，传统RAG系统受限于静态工作流，难以应对多步推理和复杂任务管理的挑战。为解决这一问题，智能体RAG系统（如DeepResearch）应运而生，支持动态检索策略、迭代上下文优化和自适应工作流，从而能够处理超越传统RAG能力的复杂搜索查询。近期进展如Search-R1展示了基于结果的强化学习带来的显著提升，其中最终答案的正确性作为奖励信号。然而，此类基于结果监督的智能体RAG方法面临探索效率低、梯度冲突和稀疏奖励信号等挑战。为克服这些挑战，我们提出利用细粒度、过程级别的奖励来提升训练稳定性、降低计算成本并提高效率。具体而言，我们引入了一种新颖的方法ReasonRAG，能够自动构建RAG-ProGuide，这是一个提供（i）查询生成、（ii）证据提取和（iii）答案生成等过程级别奖励的高质量数据集，从而通过过程监督的强化学习提升模型的内在能力。通过过程级别的策略优化，所提出的框架赋能LLMs自主调用搜索、生成查询、提取相关证据并生成最终答案。与现有方法如Search-R1和传统RAG系统相比，ReasonRAG借助RAG-ProGuide，仅使用5k训练实例就在五个基准数据集上实现了更优性能，显著低于Search-R1所需的90k训练实例。

> Retrieval-augmented generation (RAG) enhances the text generation capabilities of large language models (LLMs) by integrating external knowledge and up-to-date information. However, traditional RAG systems are limited by static workflows and lack the adaptability required for multistep reasoning and complex task management. To address these limitations, agentic RAG systems (e.g., DeepResearch) have been proposed, enabling dynamic retrieval strategies, iterative context refinement, and adaptive workflows for handling complex search queries beyond the capabilities of conventional RAG. Recent advances, such as Search-R1, have demonstrated promising gains using outcome-based reinforcement learning, where the correctness of the final answer serves as the reward signal. Nevertheless, such outcome-supervised agentic RAG methods face challenges including low exploration efficiency, gradient conflict, and sparse reward signals. To overcome these challenges, we propose to utilize fine-grained, process-level rewards to improve training stability, reduce computational costs, and enhance efficiency. Specifically, we introduce a novel method ReasonRAG that automatically constructs RAG-ProGuide, a high-quality dataset providing process-level rewards for (i) query generation, (ii) evidence extraction, and (iii) answer generation, thereby enhancing model inherent capabilities via process-supervised reinforcement learning. With the process-level policy optimization, the proposed framework empowers LLMs to autonomously invoke search, generate queries, extract relevant evidence, and produce final answers. Compared to existing approaches such as Search-R1 and traditional RAG systems, ReasonRAG, leveraging RAG-ProGuide, achieves superior performance on five benchmark datasets using only 5k training instances, significantly fewer than the 90k training instances required by Search-R1.

[Arxiv](https://arxiv.org/abs/2505.14069)