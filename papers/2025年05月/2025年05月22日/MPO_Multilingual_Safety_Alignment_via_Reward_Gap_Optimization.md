# MPO：通过优化奖励差距实现多语言安全对齐的MPO方法

发布时间：2025年05月22日

`LLM应用` `多语言处理`

> MPO: Multilingual Safety Alignment via Reward Gap Optimization

# 摘要

> 大型语言模型（LLMs）已成为全球AI应用的核心，因此需要强大的多语言安全对齐，以确保在各种语言环境中安全部署。现有的安全对齐方法如RLHF和DPO主要针对单语种，难以处理嘈杂的多语言数据。为此，我们提出了一种名为多语言奖励差距优化（MPO）的新方法，利用英语（主导语言）中良好对齐的安全能力，提升多语言环境下的安全对齐效果。MPO直接最小化主导语言与目标语言之间的奖励差距，有效转移安全能力的同时保留主导语言原有的优势。在LLaMA-3.1、Gemma-2和Qwen2.5三个大型语言模型上的广泛实验验证了MPO在多语言安全对齐方面的有效性，而不会降低其通用多语言功能。

> Large language models (LLMs) have become increasingly central to AI applications worldwide, necessitating robust multilingual safety alignment to ensure secure deployment across diverse linguistic contexts. Existing preference learning methods for safety alignment, such as RLHF and DPO, are primarily monolingual and struggle with noisy multilingual data. To address these limitations, we introduce Multilingual reward gaP Optimization (MPO), a novel approach that leverages the well-aligned safety capabilities of the dominant language (English) to improve safety alignment across multiple languages. MPO directly minimizes the reward gap difference between the dominant language and target languages, effectively transferring safety capabilities while preserving the original strengths of the dominant language. Extensive experiments on three LLMs, LLaMA-3.1, Gemma-2 and Qwen2.5, validate MPO's efficacy in multilingual safety alignment without degrading general multilingual utility.

[Arxiv](https://arxiv.org/abs/2505.16869)