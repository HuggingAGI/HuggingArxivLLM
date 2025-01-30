# 基于表格和文本的问答：LLMs与混合图的应用

发布时间：2025年01月29日

`RAG

理由：这篇论文提出了一种基于混合图的表格-文本 QA 方法，旨在通过构建统一的混合图来为 LLM 提供简洁的相关上下文，从而在零-shot 设置下提升多源表格-文本 QA 的性能。这种方法涉及到从多个数据源（表格和文本）中检索信息，并将其整合到一个统一的框架中，这与 RAG（Retrieval-Augmented Generation）的核心思想一致，即通过检索外部知识来增强生成模型的能力。因此，这篇论文应被分类为 RAG。` `数据管理` `问答系统`

> Hybrid Graphs for Table-and-Text based Question Answering using LLMs

# 摘要

> 回答需要跨结构化（表格）和非结构化（文本）数据源进行推理和聚合的问题，面临巨大挑战。现有方法依赖微调和高质量人工整理数据，但这些数据难以获取。近期大型语言模型（LLMs）的进展在零-shot 设置下对单源文本的多跳问答（QA）表现出色，但对多源表格-文本 QA 的探索仍显不足。本文提出了一种无需微调的基于混合图的表格-文本 QA 方法。我们通过构建统一的混合图，根据问题修剪信息，为 LLM 提供简洁的相关上下文。我们在 Hybrid-QA 和 OTT-QA 数据集上使用 GPT-3.5、GPT-4 和 LLaMA-3 等先进 LLMs 进行评估。结果表明，我们的方法在零-shot 性能上表现最佳，Hybrid-QA 的 Exact Match 分数提升最多 10%，OTT-QA 提升 5.4%。此外，与原始上下文相比，我们的方法减少了最多 53% 的 token 使用量。

> Answering questions that require reasoning and aggregation across both structured (tables) and unstructured (raw text) data sources presents significant challenges. Current methods rely on fine-tuning and high-quality, human-curated data, which is difficult to obtain. Recent advances in Large Language Models (LLMs) have shown promising results for multi-hop question answering (QA) over single-source text data in a zero-shot setting, yet exploration into multi-source Table-Text QA remains limited. In this paper, we present a novel Hybrid Graph-based approach for Table-Text QA that leverages LLMs without fine-tuning. Our method constructs a unified Hybrid Graph from textual and tabular data, pruning information based on the input question to provide the LLM with relevant context concisely. We evaluate our approach on the challenging Hybrid-QA and OTT-QA datasets using state-of-the-art LLMs, including GPT-3.5, GPT-4, and LLaMA-3. Our method achieves the best zero-shot performance on both datasets, improving Exact Match scores by up to 10% on Hybrid-QA and 5.4% on OTT-QA. Moreover, our approach reduces token usage by up to 53% compared to the original context.

[Arxiv](https://arxiv.org/abs/2501.17767)