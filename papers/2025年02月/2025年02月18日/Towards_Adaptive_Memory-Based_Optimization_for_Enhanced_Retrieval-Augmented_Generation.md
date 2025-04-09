# 迈向记忆优化，助力提升检索增强生成

发布时间：2025年02月18日

`RAG` `问答系统`

> Towards Adaptive Memory-Based Optimization for Enhanced Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合外部知识库中的非参数知识到模型中，作为一种有前途的方法，旨在提高响应准确性，同时减少事实性错误和幻觉现象。这种方法已被广泛应用于问答（QA）任务。然而，现有的 RAG 方法在处理开放领域 QA 任务时面临困难，因为它们执行独立的检索操作，并直接将检索到的信息整合到生成过程中，而没有维护总结性的记忆或采用自适应的检索策略，导致冗余信息产生的噪声和信息整合不足。

为了解决这些挑战，我们针对开放领域 QA 任务提出了自适应记忆优化增强的 RAG（Amber）。Amber 包含三个核心组件：基于智能体的记忆更新器、自适应信息收集器和多粒度内容过滤器，它们在迭代式记忆更新范式下协同工作。具体而言，Amber 通过多智能体协作的方式整合和优化语言模型的记忆，确保从之前的检索步骤中实现全面的知识整合。它根据累积的知识动态调整检索查询，并决定何时停止检索，从而提高检索效率和效果。此外，它通过多层级过滤无关内容来降低噪声，保留关键信息，从而提升整体模型性能。

我们在多个开放领域 QA 数据集上进行了广泛实验，结果证明了我们方法及其组件的优越性和有效性。源代码可在ootnote{https://anonymous.4open.science/r/Amber-B203/}获取。

> Retrieval-Augmented Generation (RAG), by integrating non-parametric knowledge from external knowledge bases into models, has emerged as a promising approach to enhancing response accuracy while mitigating factual errors and hallucinations. This method has been widely applied in tasks such as Question Answering (QA). However, existing RAG methods struggle with open-domain QA tasks because they perform independent retrieval operations and directly incorporate the retrieved information into generation without maintaining a summarizing memory or using adaptive retrieval strategies, leading to noise from redundant information and insufficient information integration. To address these challenges, we propose Adaptive memory-based optimization for enhanced RAG (Amber) for open-domain QA tasks, which comprises an Agent-based Memory Updater, an Adaptive Information Collector, and a Multi-granular Content Filter, working together within an iterative memory updating paradigm. Specifically, Amber integrates and optimizes the language model's memory through a multi-agent collaborative approach, ensuring comprehensive knowledge integration from previous retrieval steps. It dynamically adjusts retrieval queries and decides when to stop retrieval based on the accumulated knowledge, enhancing retrieval efficiency and effectiveness. Additionally, it reduces noise by filtering irrelevant content at multiple levels, retaining essential information to improve overall model performance. We conduct extensive experiments on several open-domain QA datasets, and the results demonstrate the superiority and effectiveness of our method and its components. The source code is available \footnote{https://anonymous.4open.science/r/Amber-B203/}.

[Arxiv](https://arxiv.org/abs/2504.05312)