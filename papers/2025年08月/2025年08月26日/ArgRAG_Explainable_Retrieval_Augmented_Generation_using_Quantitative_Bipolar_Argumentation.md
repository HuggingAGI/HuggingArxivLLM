# ArgRAG：基于定量双极论证的可解释检索增强生成

发布时间：2025年08月26日

`RAG` `医疗健康`

> ArgRAG: Explainable Retrieval Augmented Generation using Quantitative Bipolar Argumentation

# 摘要

> 检索增强生成（RAG）通过整合外部知识增强大型语言模型，然而在高风险领域存在关键局限——即对嘈杂或矛盾证据敏感，且决策过程不透明、具有随机性。为此，我们提出ArgRAG——一种可解释且可辩驳的替代方案，它采用定量双极论证框架（QBAF），以结构化推理取代黑箱推理。ArgRAG从检索文档中构建QBAF，并在渐进语义下执行确定性推理，确保决策能够被忠实地解释和辩驳。在PubHealth和RAGuard两个事实核查基准上的评估显示，ArgRAG在保持较高准确率的同时，显著提升了透明度。

> Retrieval-Augmented Generation (RAG) enhances large language models by incorporating external knowledge, yet suffers from critical limitations in high-stakes domains -- namely, sensitivity to noisy or contradictory evidence and opaque, stochastic decision-making. We propose ArgRAG, an explainable, and contestable alternative that replaces black-box reasoning with structured inference using a Quantitative Bipolar Argumentation Framework (QBAF). ArgRAG constructs a QBAF from retrieved documents and performs deterministic reasoning under gradual semantics. This allows faithfully explaining and contesting decisions. Evaluated on two fact verification benchmarks, PubHealth and RAGuard, ArgRAG achieves strong accuracy while significantly improving transparency.

[Arxiv](https://arxiv.org/abs/2508.20131)