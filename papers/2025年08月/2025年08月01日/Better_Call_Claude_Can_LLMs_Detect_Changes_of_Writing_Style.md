# 该叫Claude了：LLMs能否识别写作风格的变化？

发布时间：2025年08月01日

`LLM应用

理由：这篇论文探讨了大型语言模型在句子级别风格变化检测中的应用，具体评估了模型在特定任务中的性能，并分析了其对风格信号的敏感性。这些内容属于LLM的实际应用研究，因此归类为LLM应用。` `作者分析` `写作风格分析`

> Better Call Claude: Can LLMs Detect Changes of Writing Style?

# 摘要

> 本文研究了当前最先进的大型语言模型（LLMs）在作者分析领域最具挑战性的任务——句子级别风格变化检测中的零样本性能。通过对官方PAN~2024和2025"多作者写作风格分析"数据集进行基准测试，我们得出以下发现：

首先，最先进的生成模型对写作风格的变化非常敏感，即使是在单个句子的粒度级别也能察觉。其次，它们的准确性为该任务设立了具有挑战性的基准，超越了PAN竞赛中建议的基线水平。最后，我们研究了语义对模型预测的影响，发现最新一代的LLMs可能比之前报告的更敏感于与内容无关的纯风格信号。

> This article explores the zero-shot performance of state-of-the-art large language models (LLMs) on one of the most challenging tasks in authorship analysis: sentence-level style change detection. Benchmarking four LLMs on the official PAN~2024 and 2025 "Multi-Author Writing Style Analysis" datasets, we present several observations. First, state-of-the-art generative models are sensitive to variations in writing style - even at the granular level of individual sentences. Second, their accuracy establishes a challenging baseline for the task, outperforming suggested baselines of the PAN competition. Finally, we explore the influence of semantics on model predictions and present evidence suggesting that the latest generation of LLMs may be more sensitive to content-independent and purely stylistic signals than previously reported.

[Arxiv](https://arxiv.org/abs/2508.00680)