# Infinity-MM：利用大规模高质量指令数据提升多模态性能

发布时间：2024年10月24日

`LLM应用

理由：该论文主要讨论了如何通过扩展指令数据和生成合成数据来提升开源视觉-语言模型（VLM）的性能，并训练了一个新的VLM模型。这属于大型语言模型（LLM）在实际应用中的改进和优化，因此应归类为LLM应用。` `计算机视觉`

> Infinity-MM: Scaling Multimodal Performance with Large-Scale and High-Quality Instruction Data

# 摘要

> 视觉-语言模型（VLMs）近期进展显著，但开源指令数据的规模和质量限制了其性能，难以与闭源模型匹敌。为此，我们推出了Infinity-MM，一个包含4000万样本的大规模多模态指令数据集，经过严格的质量过滤和去重处理。此外，我们提出了一种基于开源VLMs的合成指令生成方法，利用详细的图像注释和多样化问题生成。基于这些数据，我们训练了20亿参数的VLM——Aquila-VL-2B，在同类模型中达到了SOTA性能。这表明，扩展指令数据并生成合成数据，能显著提升开源模型的性能。

> Vision-Language Models (VLMs) have recently made significant progress, but the limited scale and quality of open-source instruction data hinder their performance compared to closed-source models. In this work, we address this limitation by introducing Infinity-MM, a large-scale multimodal instruction dataset with 40 million samples, enhanced through rigorous quality filtering and deduplication. We also propose a synthetic instruction generation method based on open-source VLMs, using detailed image annotations and diverse question generation. Using this data, we trained a 2-billion-parameter VLM, Aquila-VL-2B, achieving state-of-the-art (SOTA) performance for models of similar scale. This demonstrates that expanding instruction data and generating synthetic data can significantly improve the performance of open-source models.

[Arxiv](https://arxiv.org/abs/2410.18558)