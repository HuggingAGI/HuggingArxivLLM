# # 揭秘语言模型在新闻摘要中的潜力

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要关注的是对多种语言模型在新闻摘要任务中的性能进行基准测试和评估，特别是零-shot和少-shot学习设置下的表现。这涉及到大型语言模型（LLM）在实际应用中的使用和性能评估，因此属于LLM应用的范畴。`

> Unraveling the Capabilities of Language Models in News Summarization

# 摘要

> 随着多种语言模型的引入以及对自然语言处理任务（尤其是摘要生成）的持续需求，本研究对20个最新语言模型进行了全面基准测试，重点关注新闻摘要任务中的小型模型。我们系统评估了这些模型在总结不同风格新闻文章时的能力，这些文章来自三个不同数据集。研究主要聚焦于零-shot和少-shot学习设置，并采用了一种结合自动指标、人工评估和LLM-as-a-judge的稳健评估方法。有趣的是，少-shot学习中的示例并未提升模型性能，有时甚至导致摘要质量下降。这主要归因于参考摘要质量不佳，影响了模型表现。此外，研究结果显示，GPT-3.5-Turbo和GPT-4凭借其先进能力表现卓越。然而，在公开模型中，Qwen1.5-7B、SOLAR-10.7B-Instruct-v1.0、Meta-Llama-3-8B和Zephyr-7B-Beta等模型展现出显著潜力，成为新闻摘要任务中大型模型的有力竞争者。

> Given the recent introduction of multiple language models and the ongoing demand for improved Natural Language Processing tasks, particularly summarization, this work provides a comprehensive benchmarking of 20 recent language models, focusing on smaller ones for the news summarization task. In this work, we systematically test the capabilities and effectiveness of these models in summarizing news article texts which are written in different styles and presented in three distinct datasets. Specifically, we focus in this study on zero-shot and few-shot learning settings and we apply a robust evaluation methodology that combines different evaluation concepts including automatic metrics, human evaluation, and LLM-as-a-judge. Interestingly, including demonstration examples in the few-shot learning setting did not enhance models' performance and, in some cases, even led to worse quality of the generated summaries. This issue arises mainly due to the poor quality of the gold summaries that have been used as reference summaries, which negatively impacts the models' performance. Furthermore, our study's results highlight the exceptional performance of GPT-3.5-Turbo and GPT-4, which generally dominate due to their advanced capabilities. However, among the public models evaluated, certain models such as Qwen1.5-7B, SOLAR-10.7B-Instruct-v1.0, Meta-Llama-3-8B and Zephyr-7B-Beta demonstrated promising results. These models showed significant potential, positioning them as competitive alternatives to large models for the task of news summarization.

[Arxiv](https://arxiv.org/abs/2501.18128)