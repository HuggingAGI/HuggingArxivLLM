# 语言模型中的同质性偏差：差分采样不确定性的视角

发布时间：2025年01月31日

`LLM理论

**解释**：这篇论文主要探讨了LLMs和VLMs在生成文本时对边缘化群体的同质性偏差，并提出了这种偏差可能源于推理时token采样的概率分布差异。论文通过分析不确定性度量（如熵、困惑度和区分概率）来验证这一假设。这些内容属于对LLM内部机制和理论的研究，因此分类为“LLM理论”。` `人工智能` `社会研究`

> Homogeneity Bias as Differential Sampling Uncertainty in Language Models

# 摘要

> 先前的研究表明，LLMs和VLMs对边缘化群体的表征比主导群体更加同质化，但其背后的机制尚不明确。我们提出，这种偏差源于推理时token采样的概率分布差异。通过分析熵、困惑度和区分概率等不确定性度量，我们发现，在GPT-4 Turbo和Llama-3.2等模型中，生成边缘化群体（如非裔美国人和女性）文本时，token采样比生成主导群体（如白人和男性）文本时更加确定性。尽管这些发现有助于解释部分模型的同质性偏差，但并非所有VLMs都表现出相同模式，这表明AI中的同质性偏差可能由多种机制共同作用。

> Prior research show that Large Language Models (LLMs) and Vision-Language Models (VLMs) represent marginalized groups more homogeneously than dominant groups. However, the mechanisms underlying this homogeneity bias remain relatively unexplored. We propose that this bias emerges from systematic differences in the probability distributions from which tokens are sampled at inference-time. Analyzing three measures of uncertainty in token sampling distributions-entropy, perplexity, and probability of differentiation-we find that in some models, specifically GPT-4 Turbo and Llama-3.2, tokens are sampled more deterministically when generating texts about marginalized groups (i.e., Black Americans and women) compared to their dominant group counterparts (i.e., White Americans and men). While these findings may help explain homogeneity bias in certain models, the patterns did not replicate across all VLMs tested, suggesting multiple mechanisms may contribute to homogeneity bias in AI.

[Arxiv](https://arxiv.org/abs/2501.19337)