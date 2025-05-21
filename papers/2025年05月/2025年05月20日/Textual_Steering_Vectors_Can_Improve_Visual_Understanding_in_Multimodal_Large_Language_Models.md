# # 文本引导向量可增强多模态大型语言模型的视觉理解

发布时间：2025年05月20日

`LLM应用` `人工智能` `计算机视觉`

> Textual Steering Vectors Can Improve Visual Understanding in Multimodal Large Language Models

# 摘要

> 引导方法无需修改参数即可有效且精准地引导大型语言模型（LLMs）行为。然而，多模态大型语言模型（MLLMs）尚未享受到相同的技术优势，这主要归因于它们的近期发展和架构多样性。受此启发，我们研究了通过稀疏自编码器（SAEs）、均值漂移和线性探测，从仅文本的LLM主干中提取的向量是否可以用于引导MLLMs。研究发现，基于文本的引导方法能显著提升多种MLLM架构和视觉任务的多模态准确性。特别地，均值漂移在CV-Bench上的空间关系准确率提升了+7.3%，计数准确率提升了+3.3%，表现优于提示方法，并对分布外数据集展现了强大的泛化能力。这些结果凸显了文本引导向量作为增强MLLMs接地能力的强大且高效机制，且仅需极小的额外数据收集和计算开销。

> Steering methods have emerged as effective and targeted tools for guiding large language models' (LLMs) behavior without modifying their parameters. Multimodal large language models (MLLMs), however, do not currently enjoy the same suite of techniques, due in part to their recency and architectural diversity. Inspired by this gap, we investigate whether MLLMs can be steered using vectors derived from their text-only LLM backbone, via sparse autoencoders (SAEs), mean shift, and linear probing. We find that text-derived steering consistently enhances multimodal accuracy across diverse MLLM architectures and visual tasks. In particular, mean shift boosts spatial relationship accuracy on CV-Bench by up to +7.3% and counting accuracy by up to +3.3%, outperforming prompting and exhibiting strong generalization to out-of-distribution datasets. These results highlight textual steering vectors as a powerful, efficient mechanism for enhancing grounding in MLLMs with minimal additional data collection and computational overhead.

[Arxiv](https://arxiv.org/abs/2505.14071)