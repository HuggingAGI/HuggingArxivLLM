# 双向知识蒸馏提升大语言模型的序列推荐能力

发布时间：2025年05月23日

`LLM应用` `推荐系统` `电子商务`

> Bidirectional Knowledge Distillation for Enhancing Sequential Recommendation with Large Language Models

# 摘要

> 大型语言模型（LLMs）在语义理解和生成方面表现出色，为序列推荐任务提供了极具潜力的解决方案。然而，与传统推荐模型（CRMs）结合时，LLMs常面临推理成本高和静态知识转移的挑战。本文提出了一种全新的互蒸馏框架LLMD4Rec，实现了基于LLM和CRM的推荐系统之间的动态双向知识交换。与传统单向蒸馏不同，LLMD4Rec通过交替优化两个模型，迭代提升推荐效果，增强CRMs的语义理解能力，并通过用户-物品交互中的协作信号丰富LLMs的知识。借助样本级自适应加权和输出分布对齐，我们的方法无需额外参数即可实现高效的知识转移。真实数据集的大量实验表明，LLMD4Rec在多个基准测试中显著提升了推荐准确性，同时保持了推理成本不变。这一方法为结合LLMs与CRMs的优势，构建高效的序列推荐系统提供了一种可扩展且高效的解决方案。

> Large language models (LLMs) have demonstrated exceptional performance in understanding and generating semantic patterns, making them promising candidates for sequential recommendation tasks. However, when combined with conventional recommendation models (CRMs), LLMs often face challenges related to high inference costs and static knowledge transfer methods. In this paper, we propose a novel mutual distillation framework, LLMD4Rec, that fosters dynamic and bidirectional knowledge exchange between LLM-centric and CRM-based recommendation systems. Unlike traditional unidirectional distillation methods, LLMD4Rec enables iterative optimization by alternately refining both models, enhancing the semantic understanding of CRMs and enriching LLMs with collaborative signals from user-item interactions. By leveraging sample-wise adaptive weighting and aligning output distributions, our approach eliminates the need for additional parameters while ensuring effective knowledge transfer. Extensive experiments on real-world datasets demonstrate that LLMD4Rec significantly improves recommendation accuracy across multiple benchmarks without increasing inference costs. This method provides a scalable and efficient solution for combining the strengths of both LLMs and CRMs in sequential recommendation systems.

[Arxiv](https://arxiv.org/abs/2505.18120)