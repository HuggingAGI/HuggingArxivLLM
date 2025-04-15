# MMKB-RAG：一个多模态知识增强检索生成框架

发布时间：2025年04月14日

`RAG` `计算机视觉` `问答系统`

> MMKB-RAG: A Multi-Modal Knowledge-Based Retrieval-Augmented Generation Framework

# 摘要

> 近年来，大型语言模型（LLMs）和多模态大型语言模型取得了显著进展。然而，这些模型仍完全依赖于其参数化的知识储备，这限制了它们生成最新信息的能力，同时增加了生成错误内容的风险。检索增强生成（RAG）通过整合外部数据源部分缓解了这些挑战，但对数据库和检索系统的依赖可能引入不相关或不准确的文档，最终损害性能和推理质量。本文中，我们提出了一种新型的多模态知识增强检索生成框架（MMKB-RAG），该框架利用模型自身的知识边界动态生成语义标签以优化检索过程。这种策略实现了对检索文档的联合筛选，仅保留最相关和最准确的参考资料。在基于知识的视觉问答任务上的广泛实验验证了我们方法的有效性：在E-VQA数据集上，我们的方法在单跳子集上的性能提升了+4.2%，在完整数据集上提升了+0.4%。而在InfoSeek数据集上，我们的方法在未见问题子集上提升了+7.8%，在未见实体子集上提升了+8.2%，在完整数据集上提升了+8.1%。这些结果凸显了与当前最先进的多模态大型语言模型和RAG框架相比，我们在准确性和鲁棒性方面取得了显著提升。

> Recent advancements in large language models (LLMs) and multi-modal LLMs have been remarkable. However, these models still rely solely on their parametric knowledge, which limits their ability to generate up-to-date information and increases the risk of producing erroneous content. Retrieval-Augmented Generation (RAG) partially mitigates these challenges by incorporating external data sources, yet the reliance on databases and retrieval systems can introduce irrelevant or inaccurate documents, ultimately undermining both performance and reasoning quality. In this paper, we propose Multi-Modal Knowledge-Based Retrieval-Augmented Generation (MMKB-RAG), a novel multi-modal RAG framework that leverages the inherent knowledge boundaries of models to dynamically generate semantic tags for the retrieval process. This strategy enables the joint filtering of retrieved documents, retaining only the most relevant and accurate references. Extensive experiments on knowledge-based visual question-answering tasks demonstrate the efficacy of our approach: on the E-VQA dataset, our method improves performance by +4.2\% on the Single-Hop subset and +0.4\% on the full dataset, while on the InfoSeek dataset, it achieves gains of +7.8\% on the Unseen-Q subset, +8.2\% on the Unseen-E subset, and +8.1\% on the full dataset. These results highlight significant enhancements in both accuracy and robustness over the current state-of-the-art MLLM and RAG frameworks.

[Arxiv](https://arxiv.org/abs/2504.10074)