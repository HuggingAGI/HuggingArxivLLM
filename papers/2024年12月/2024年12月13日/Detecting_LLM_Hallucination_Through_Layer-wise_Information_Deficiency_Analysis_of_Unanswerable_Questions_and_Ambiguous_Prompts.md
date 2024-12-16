# 通过分层信息缺失来检测 LLM 的幻觉：对无法回答的问题和模糊提示的分析

发布时间：2024年12月13日

`LLM理论` `语言模型` `安全关键领域`

> Detecting LLM Hallucination Through Layer-wise Information Deficiency: Analysis of Unanswerable Questions and Ambiguous Prompts

# 摘要

> 大型语言模型（LLMs）常常给出自信却不准确的回应，这给在安全关键领域的运用带来了显著风险。我们给出了一种新的办法，即通过对处理上下文不充分或模糊的输入时模型各层间的信息流进行系统性分析，来检测模型的幻觉。我们的研究发现，幻觉体现为层间传输中的可用信息匮乏。现有的方法主要聚焦于最终层的输出分析，而我们表明，追踪跨层信息动态（$\mathcal{L}$I）能为模型的可靠性提供有力的指标，兼顾了计算过程中的信息增益和损失。$\mathcal{L}$I 无需额外训练或架构修改，能立即与通用 LLMs 集成，从而提升模型的可靠性。

> Large language models (LLMs) frequently generate confident yet inaccurate responses, introducing significant risks for deployment in safety-critical domains. We present a novel approach to detecting model hallucination through systematic analysis of information flow across model layers when processing inputs with insufficient or ambiguous context. Our investigation reveals that hallucination manifests as usable information deficiencies in inter-layer transmissions. While existing approaches primarily focus on final-layer output analysis, we demonstrate that tracking cross-layer information dynamics ($\mathcal{L}$I) provides robust indicators of model reliability, accounting for both information gain and loss during computation. $\mathcal{L}$I improves model reliability by immediately integrating with universal LLMs without additional training or architectural modifications.

[Arxiv](https://arxiv.org/abs/2412.10246)