# Hydra：跨源结构化增强大语言模型推理

发布时间：2025年05月23日

`RAG` `知识图谱`

> Hydra: Structured Cross-Source Enhanced Large Language Model Reasoning

# 摘要

> 检索增强生成（RAG）通过整合外部知识来提升大型语言模型（LLMs）的能力。当前的混合 RAG 系统从知识图谱（KG）和文本文档中检索证据以支持 LLM 的推理过程。然而，现有方法在处理多跳推理、多实体问题、多源验证以及有效图结构利用方面仍面临诸多挑战。为了解决这些局限性，我们提出了 Hydra——一个无需训练的框架，它通过统一图结构、文档语义和来源可靠性，支持 LLM 的深度且忠实推理。

Hydra 通过结合结构化与非结构化检索的智能体驱动探索，有效处理多跳和多实体问题，同时提升证据的多样性和精确性。针对多源验证问题，Hydra 采用三因素跨源验证方法（来源可信度评估、跨源相互印证、实体路径对齐），在主题相关性与跨模态一致性之间取得平衡。借助图结构，Hydra 实现异质来源的融合，指导高效探索，同时尽早剔除噪声。

在七项基准数据集上的全面实验表明，Hydra 在与 GPT-3.5 的结合中实现了所有基准的整体最优性能，相较于强大的混合基线 ToG-2，平均提升了 20.3%，最高可达 30.1%。此外，Hydra 还能使较小规模的模型（如 Llama-3.1-8B）实现与 GPT-4-Turbo 相当的推理性能。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) by incorporating external knowledge. Current hybrid RAG system retrieves evidence from both knowledge graphs (KGs) and text documents to support LLM reasoning. However, it faces challenges like handling multi-hop reasoning, multi-entity questions, multi-source verification, and effective graph utilization. To address these limitations, we present Hydra, a training-free framework that unifies graph topology, document semantics, and source reliability to support deep, faithful reasoning in LLMs. Hydra handles multi-hop and multi-entity problems through agent-driven exploration that combines structured and unstructured retrieval, increasing both diversity and precision of evidence. To tackle multi-source verification, Hydra uses a tri-factor cross-source verification (source trustworthiness assessment, cross-source corroboration, and entity-path alignment), to balance topic relevance with cross-modal agreement. By leveraging graph structure, Hydra fuses heterogeneous sources, guides efficient exploration, and prunes noise early. Comprehensive experiments on seven benchmark datasets show that Hydra achieves overall state-of-the-art results on all benchmarks with GPT-3.5, outperforming the strong hybrid baseline ToG-2 by an average of 20.3% and up to 30.1%. Furthermore, Hydra enables smaller models (e.g., Llama-3.1-8B) to achieve reasoning performance comparable to that of GPT-4-Turbo.

[Arxiv](https://arxiv.org/abs/2505.17464)