# BRIGHT+: 升级版 BRIGHT 基准，整合 MARCUS 多智能体 RAG 清理套件

发布时间：2025年06月08日

`RAG` `信息检索`

> BRIGHT+: Upgrading the BRIGHT Benchmark with MARCUS, a Multi-Agent RAG Clean-Up Suite

# 摘要

> 检索增强生成（RAG）系统需要结构干净且语义连贯的语料库。BRIGHT 是一个最近推出的具有影响力的基准测试，旨在评估跨多样化、高推理领域的复杂多跳检索能力。然而，其实际效果受到常见网络爬取 artifacts（如内容冗余和语义不连续性）的限制，这些因素会损害检索准确性及下游推理能力。值得注意的是，我们发现这些问题主要集中在七个基于 StackExchange 的子领域中，而其他领域（如编码和定理相关内容）则相对较为干净。

    本研究中，我们提出了 MARCUS，一个多智能体管道，利用大型语言模型（LLMs）系统性地清理并重新整理 BRIGHT，生成更高质量的语料库：BRIGHT-Plus。MARcus 部署了专门的智能体用于结构噪声去除和语义分段，同时保留包含答案的片段并提升上下文完整性。实验评估表明，BRIGHT-Plus 在多样化的检索器上均实现了在检索准确性和多跳推理方面的显著且一致的提升。我们发布了 BRIGHT-Plus 语料库及 MARCUS 管道，以支持未来面向健壮推理的检索研究。

> Retrieval-Augmented Generation (RAG) systems require corpora that are both structurally clean and semantically coherent. BRIGHT is a recent and influential benchmark designed to evaluate complex multi-hop retrieval across diverse, high-reasoning domains. However, its practical effectiveness is limited by common web-crawled artifacts - such as content redundancy and semantic discontinuity - that impair retrieval accuracy and downstream reasoning. Notably, we find that such issues are concentrated in seven StackExchange-derived subdomains, while other domains (e.g., Coding and Theorem-based content) remain relatively clean.
  In this study, we present MARCUS, a multi-agent pipeline that leverages large language models (LLMs) to systematically clean and re-chunk BRIGHT into a higher-quality corpus: BRIGHT-Plus. MARCUS applies dedicated agents for structural noise removal and semantic segmentation, preserving answer-bearing spans while improving contextual integrity. Experimental evaluations demonstrate that BRIGHT-Plus yields consistent and significant improvements in both retrieval accuracy and multi-hop reasoning across a diverse set of retrievers. We release both the BRIGHT-Plus corpus and the MARCUS pipeline to support future research on robust, reasoning-centric retrieval.

[Arxiv](https://arxiv.org/abs/2506.07116)