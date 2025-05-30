# StrucSum：利用大语言模型实现长文档抽取式摘要的基于图结构的推理方法

发布时间：2025年05月28日

`LLM应用

论文摘要：大型语言模型（LLMs）在零样本摘要任务中表现出色，但在处理长文本的结构建模和关键信息提取方面仍有不足。本研究提出了一种无需训练的提示框架——StrucSum，通过句子级别的图结构增强LLM的推理能力。StrucSum采用三种策略将结构信号注入提示：面向局部上下文的邻居感知提示（NAP）、用于重要性评估的中心性感知提示（CAP），以及用于高效输入缩减的中心性引导掩码（CGM）。在ArXiv、PubMed和Multi-News数据集上的实验表明，与无监督基线和普通提示方法相比，StrucSum显著提升了摘要质量和事实一致性。特别在ArXiv数据集上，StrucSum使FactCC和SummaC分别提升了19.2和9.7分，表明摘要与源内容的对齐度显著增强。这些结果表明，结构感知提示是一种简单而有效的方法，适用于基于LLMs的零样本抽取式摘要任务，且无需任何训练或特定任务调整。` `文本处理`

> StrucSum: Graph-Structured Reasoning for Long Document Extractive Summarization with LLMs

# 摘要

> 大型语言模型（LLMs）在零样本摘要任务中表现出色，但在处理长文本的结构建模和关键信息提取方面仍有不足。本研究提出了一种无需训练的提示框架——StrucSum，通过句子级别的图结构增强LLM的推理能力。StrucSum采用三种策略将结构信号注入提示：面向局部上下文的邻居感知提示（NAP）、用于重要性评估的中心性感知提示（CAP），以及用于高效输入缩减的中心性引导掩码（CGM）。在ArXiv、PubMed和Multi-News数据集上的实验表明，与无监督基线和普通提示方法相比，StrucSum显著提升了摘要质量和事实一致性。特别在ArXiv数据集上，StrucSum使FactCC和SummaC分别提升了19.2和9.7分，表明摘要与源内容的对齐度显著增强。这些结果表明，结构感知提示是一种简单而有效的方法，适用于基于LLMs的零样本抽取式摘要任务，且无需任何训练或特定任务调整。

> Large language models (LLMs) have shown strong performance in zero-shot summarization, but often struggle to model document structure and identify salient information in long texts. In this work, we introduce StrucSum, a training-free prompting framework that enhances LLM reasoning through sentence-level graph structures. StrucSum injects structural signals into prompts via three targeted strategies: Neighbor-Aware Prompting (NAP) for local context, Centrality-Aware Prompting (CAP) for importance estimation, and Centrality-Guided Masking (CGM) for efficient input reduction. Experiments on ArXiv, PubMed, and Multi-News demonstrate that StrucSum consistently improves both summary quality and factual consistency over unsupervised baselines and vanilla prompting. Notably, on ArXiv, it boosts FactCC and SummaC by 19.2 and 9.7 points, indicating stronger alignment between summaries and source content. These findings suggest that structure-aware prompting is a simple yet effective approach for zero-shot extractive summarization with LLMs, without any training or task-specific tuning.

[Arxiv](https://arxiv.org/abs/2505.22950)