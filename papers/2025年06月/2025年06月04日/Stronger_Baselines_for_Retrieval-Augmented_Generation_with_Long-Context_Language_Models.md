# 长上下文语言模型的增强检索生成更强基线

发布时间：2025年06月04日

`RAG` `问答系统`

> Stronger Baselines for Retrieval-Augmented Generation with Long-Context Language Models

# 摘要

> 在长上下文语言模型（LMs）能够一次性处理数万个标记的背景下，多阶段检索增强生成（RAG）管道是否仍然比一阶段方法更具优势？我们通过系统性扩展的标记预算进行受控评估，将两种多阶段管道（ReadAgent 和 RAPTOR）与三个基线（包括保留原始段落顺序的简单检索后阅读方法 DOS RAG）进行对比。尽管设计简单，DOS RAG 在多个长上下文问答基准测试中表现优异。我们建议将 DOS RAG 作为未来 RAG 评估的简单而强大的基线，并结合新兴的嵌入和语言模型，评估复杂性和有效性在模型能力发展中的权衡。

> With the rise of long-context language models (LMs) capable of processing tens of thousands of tokens in a single pass, do multi-stage retrieval-augmented generation (RAG) pipelines still offer measurable benefits over simpler, single-stage approaches? To assess this question, we conduct a controlled evaluation for QA tasks under systematically scaled token budgets, comparing two recent multi-stage pipelines, ReadAgent and RAPTOR, against three baselines, including DOS RAG (Document's Original Structure RAG), a simple retrieve-then-read method that preserves original passage order. Despite its straightforward design, DOS RAG consistently matches or outperforms more intricate methods on multiple long-context QA benchmarks. We recommend establishing DOS RAG as a simple yet strong baseline for future RAG evaluations, pairing it with emerging embedding and language models to assess trade-offs between complexity and effectiveness as model capabilities evolve.

[Arxiv](https://arxiv.org/abs/2506.03989)