# # 强化信息优化在长文本检索增强生成中的应用

发布时间：2025年05月27日

`RAG` `问答系统`

> Reinforced Informativeness Optimization for Long-Form Retrieval-Augmented Generation

# 摘要

> 长文本问答（LFQA）要求生成连贯且段落长度的答案，这对大型语言模型提出了独特挑战。尽管检索增强生成（RAG）系统已作为一种有前景的解决方案出现，但现有研究仍面临三大关键限制：用于长文本生成的高质量训练数据稀缺、扩展输出中幻觉风险的累积，以及缺乏可靠的事实完整性评估指标。本文提出RioRAG，一个基于强化学习（RL）的创新框架，通过强化信息优化推动长文本RAG的发展。我们的方法在两个核心创新上实现了突破。首先，我们开发了一种基于强化信息优化的RL训练范式，直接优化信息量，有效解决了传统RAG系统中深度思考能力的不足，且无需昂贵的监督数据。其次，我们提出了一种基于 nugget 的分层奖励建模方法，通过三阶段流程实现对长文本答案的精准评估：从每个源网页中提取 nugget，构建 nugget 声明清单，以及基于事实对齐计算奖励。在 LongFact 和 RAGChecker 两个 LFQA 基准数据集上的大量实验验证了所提方法的有效性。我们的代码可在 https://github.com/RUCAIBox/RioRAG 获取。

> Long-form question answering (LFQA) presents unique challenges for large language models, requiring the synthesis of coherent, paragraph-length answers. While retrieval-augmented generation (RAG) systems have emerged as a promising solution, existing research struggles with key limitations: the scarcity of high-quality training data for long-form generation, the compounding risk of hallucination in extended outputs, and the absence of reliable evaluation metrics for factual completeness. In this paper, we propose RioRAG, a novel reinforcement learning (RL) framework that advances long-form RAG through reinforced informativeness optimization. Our approach introduces two fundamental innovations to address the core challenges. First, we develop an RL training paradigm of reinforced informativeness optimization that directly optimizes informativeness and effectively addresses the slow-thinking deficit in conventional RAG systems, bypassing the need for expensive supervised data. Second, we propose a nugget-centric hierarchical reward modeling approach that enables precise assessment of long-form answers through a three-stage process: extracting the nugget from every source webpage, constructing a nugget claim checklist, and computing rewards based on factual alignment. Extensive experiments on two LFQA benchmarks LongFact and RAGChecker demonstrate the effectiveness of the proposed method. Our codes are available at https://github.com/RUCAIBox/RioRAG.

[Arxiv](https://arxiv.org/abs/2505.20825)