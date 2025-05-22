# 大型语言模型助力数据合成

发布时间：2025年05月20日

`LLM应用` `数据合成` `社会科学`

> Large Language Models for Data Synthesis

# 摘要

> 生成能够真实反映现实世界分布统计结构的合成数据是数据建模中的基本挑战。传统方法通常依赖于强烈的参数假设或手动结构设计，在高维或异质领域中表现乏力。大型语言模型（LLMs）的最新进展揭示了它们作为现实世界分布的灵活、高维先验的潜力。然而，当应用于数据合成时，标准的LLM采样效率低下，受固定上下文限制，且无法确保统计对齐。鉴于此，我们引入了LLMSynthor，这是一个通用的数据合成框架，它将LLMs转化为由分布反馈引导的结构感知模拟器。LLMSynthor将LLM视为非参数copula模拟器，用于建模高阶依赖关系，并引入LLM建议采样来生成有根据的建议分布，从而提高采样效率而无需拒绝。通过最小化摘要统计量空间中的差异，迭代合成循环对齐真实和合成数据，同时逐渐揭示并完善潜在的生成结构。我们在受控和现实环境中使用隐私敏感领域（如电子商务、人口和移动性）的异构数据集（涵盖结构化和非结构化格式）对LLMSynthor进行了评估。LLMSynthor生成的合成数据展示了高统计保真度、实用性和跨数据适应性，使其成为经济学、社会科学、城市研究等领域的宝贵工具。


> Generating synthetic data that faithfully captures the statistical structure of real-world distributions is a fundamental challenge in data modeling. Classical approaches often depend on strong parametric assumptions or manual structural design and struggle in high-dimensional or heterogeneous domains. Recent progress in Large Language Models (LLMs) reveals their potential as flexible, high-dimensional priors over real-world distributions. However, when applied to data synthesis, standard LLM-based sampling is inefficient, constrained by fixed context limits, and fails to ensure statistical alignment. Given this, we introduce LLMSynthor, a general framework for data synthesis that transforms LLMs into structure-aware simulators guided by distributional feedback. LLMSynthor treats the LLM as a nonparametric copula simulator for modeling high-order dependencies and introduces LLM Proposal Sampling to generate grounded proposal distributions that improve sampling efficiency without requiring rejection. By minimizing discrepancies in the summary statistics space, the iterative synthesis loop aligns real and synthetic data while gradually uncovering and refining the latent generative structure. We evaluate LLMSynthor in both controlled and real-world settings using heterogeneous datasets in privacy-sensitive domains (e.g., e-commerce, population, and mobility) that encompass both structured and unstructured formats. The synthetic data produced by LLMSynthor shows high statistical fidelity, practical utility, and cross-data adaptability, positioning it as a valuable tool across economics, social science, urban studies, and beyond.

[Arxiv](https://arxiv.org/abs/2505.14752)