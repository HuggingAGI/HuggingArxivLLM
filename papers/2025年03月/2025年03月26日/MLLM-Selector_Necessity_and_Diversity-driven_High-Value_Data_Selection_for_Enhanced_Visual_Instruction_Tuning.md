# MLLM-Selector：从必要性与多样性出发，实现高价值数据选择，助力视觉指令微调的优化提升。

发布时间：2025年03月26日

`LLM应用` `人工智能`

> MLLM-Selector: Necessity and Diversity-driven High-Value Data Selection for Enhanced Visual Instruction Tuning

# 摘要

> 视觉指令调优（VIT）已成为使多模态大型语言模型（MLLMs）熟练遵循用户指令的关键技术。然而，关于高质量指令调优数据的属性及其自动化选择框架的理解仍然存在重大空白。为此，我们推出了MLLM-Selector，这是一种通过权衡必要性和多样性来识别VIT中有价值数据的自动化方法。我们的方法首先从VIT数据池中随机采样一个子集来微调预训练模型，从而创建一个具有初步指令遵循能力的种子模型。然后，利用该种子模型，我们计算VIT数据池中每个样本的必要性分数，以识别对提升模型性能至关重要的样本。研究结果强调了在数据选择中混合必要性和多样性的的重要性，从而催生了MLLM-Selector——一种将必要性评分与战略抽样相结合的方法，以实现更优的数据精炼。实证结果表明，在相同的实验条件下，MLLM-Selector在某些基准上使用不到1%的数据就超过了LLaVA-1.5，并且在使用不到50%的数据时，在所有经过验证的基准上始终表现出更优的性能。

> Visual instruction tuning (VIT) has emerged as a crucial technique for enabling multi-modal large language models (MLLMs) to follow user instructions adeptly. Yet, a significant gap persists in understanding the attributes of high-quality instruction tuning data and frameworks for its automated selection. To address this, we introduce MLLM-Selector, an automated approach that identifies valuable data for VIT by weighing necessity and diversity. Our process starts by randomly sampling a subset from the VIT data pool to fine-tune a pretrained model, thus creating a seed model with an initial ability to follow instructions. Then, leveraging the seed model, we calculate necessity scores for each sample in the VIT data pool to identify samples pivotal for enhancing model performance. Our findings underscore the importance of mixing necessity and diversity in data choice, leading to the creation of MLLM-Selector, our methodology that fuses necessity scoring with strategic sampling for superior data refinement. Empirical results indicate that within identical experimental conditions, MLLM-Selector surpasses LLaVA-1.5 in some benchmarks with less than 1% of the data and consistently exceeds performance across all validated benchmarks when using less than 50%.

[Arxiv](https://arxiv.org/abs/2503.20502)