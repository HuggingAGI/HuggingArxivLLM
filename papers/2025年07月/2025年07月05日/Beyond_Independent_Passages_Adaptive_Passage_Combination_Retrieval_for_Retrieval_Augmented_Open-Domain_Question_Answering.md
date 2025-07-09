# 超越独立段落：在检索增强的开放域问答中实现自适应段落组合检索

发布时间：2025年07月05日

`RAG` `问答系统`

> Beyond Independent Passages: Adaptive Passage Combination Retrieval for Retrieval Augmented Open-Domain Question Answering

# 摘要

> 检索增强生成（RAG）通过在推理时整合外部文档来提升大型语言模型（LLMs）的能力，使模型无需昂贵的重新训练就能获取最新知识。然而，传统的RAG方法独立检索段落，常常导致上下文冗余、噪声或多样性不足，特别是在嘈杂语料库和多跳问题中尤为突出。为了解决这一问题，我们提出了自适应段落组合检索（AdaPCR），一个基于黑盒语言模型的开放领域问答新框架。AdaPCR通过将段落组合视为检索和重新排序的单元，显式建模段落之间的依赖关系。它包含两个部分：使用拼接段落的上下文感知查询重写，以及通过与下游答案可能性对齐的预测目标训练的重新排序步骤。至关重要的是，AdaPCR能够自适应选择检索段落数量，无需额外的停止模块。在多个问答基准上的实验表明，AdaPCR超越了基线方法，尤其在多跳推理方面表现突出，证明了建模段落间依赖关系对提升检索效果的有效性。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) by incorporating external documents at inference time, enabling up-to-date knowledge access without costly retraining. However, conventional RAG methods retrieve passages independently, often leading to redundant, noisy, or insufficiently diverse context-particularly problematic - particularly problematic in noisy corpora and for multi-hop questions. To address this, we propose Adaptive Passage Combination Retrieval (AdaPCR), a novel framework for open-domain question answering with black-box LMs. AdaPCR explicitly models dependencies between passages by considering passage combinations as units for retrieval and reranking. It consists of a context-aware query reformulation using concatenated passages, and a reranking step trained with a predictive objective aligned with downstream answer likelihood. Crucially, AdaPCR adaptively selects the number of retrieved passages without additional stopping modules. Experiments across several QA benchmarks show that AdaPCR outperforms baselines, particularly in multi-hop reasoning, demonstrating the effectiveness of modeling inter-passage dependencies for improved retrieval.

[Arxiv](https://arxiv.org/abs/2507.04069)