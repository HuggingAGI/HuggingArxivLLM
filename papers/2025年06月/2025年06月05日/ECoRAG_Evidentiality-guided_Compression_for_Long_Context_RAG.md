# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月05日

`RAG` `问答系统` `信息检索`

> ECoRAG: Evidentiality-guided Compression for Long Context RAG

# 摘要

> 大型语言模型（LLMs）在开放领域问答任务（ODQA）中表现出色，得益于检索增强生成（RAG）方法对外部文档的利用。然而，处理更长上下文时，现有压缩方法未能有效过滤非证据性信息，限制了LLM在RAG任务中的性能。为此，我们提出了基于证据性的**ECoRAG**框架。ECoRAG通过基于证据性的压缩检索到的文档，确保答案生成有正确的证据支持，从而提升LLM的表现。此外，ECoRAG还会检查压缩内容是否提供了充分的证据，若不充分则会继续检索，直到满足要求。实验结果表明，ECoRAG在开放领域问答任务中显著提升了LLM的表现，超越了现有的压缩方法。此外，ECoRAG具有很高的成本效益，因为它不仅降低了延迟，还通过仅保留生成正确答案所需的信息来最小化令牌使用。代码可在https://github.com/ldilab/ECoRAG获取。

> Large Language Models (LLMs) have shown remarkable performance in Open-Domain Question Answering (ODQA) by leveraging external documents through Retrieval-Augmented Generation (RAG). To reduce RAG overhead, from longer context, context compression is necessary. However, prior compression methods do not focus on filtering out non-evidential information, which limit the performance in LLM-based RAG. We thus propose Evidentiality-guided RAG, or \textbf{ECoRAG} framework. ECoRAG improves LLM performance by compressing retrieved documents based on evidentiality, ensuring whether answer generation is supported by the correct evidence. As an additional step, ECoRAG reflects whether the compressed content provides sufficient evidence, and if not, retrieves more until sufficient. Experiments show that ECoRAG improves LLM performance on ODQA tasks, outperforming existing compression methods. Furthermore, ECoRAG is highly cost-efficient, as it not only reduces latency but also minimizes token usage by retaining only the necessary information to generate the correct answer. Code is available at https://github.com/ldilab/ECoRAG.

[Arxiv](https://arxiv.org/abs/2506.05167)