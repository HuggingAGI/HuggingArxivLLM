# 大型语言模型能否助力因果发现的实验设计？

发布时间：2025年03月02日

`LLM应用` `科学发现` `因果发现`

> Can Large Language Models Help Experimental Design for Causal Discovery?

# 摘要

> 设计实验并选择干预目标一直是科学和因果发现中的难题。仅凭观察数据识别因果结构本身就颇具挑战性。干预数据对因果发现至关重要，但获取足够的干预数据往往成本高昂且耗时。传统方法通常依赖不确定性或梯度信号来确定干预目标，但在干预数据有限的情况下，数值方法可能因引导信号估计不准确而效果欠佳。我们提出了一种全新的方法：借助大型语言模型（LLMs）丰富的知识库，辅助因果发现中的干预目标定位。具体来说，我们推出了\oursfull (\ours) — 一个强大的框架，通过结合LLMs来增强现有数值方法，提升因果发现中的干预定位效果。在4个现实基准测试中，\ours不仅超越了现有方法，甚至超过了人类的表现，充分证明了LLMs在科学发现实验设计中的巨大潜力。

> Designing proper experiments and selecting optimal intervention targets is a longstanding problem in scientific or causal discovery. Identifying the underlying causal structure from observational data alone is inherently difficult.Obtaining interventional data, on the other hand, is crucial to causal discovery, yet it is usually expensive and time-consuming to gather sufficient interventional data to facilitate causal discovery.Previous approaches commonly utilize uncertainty or gradient signals to determine the intervention targets. However, numerical-based approaches may yield suboptimal results due to the inaccurate estimation of the guiding signals at the beginning when with limited interventional data. In this work, we investigate a different approach, whether we can leverage Large Language Models (LLMs) to assist with the intervention targeting in causal discovery by making use of the rich world knowledge about the experimental design in LLMs.Specifically, we present \oursfull (\ours) -- a robust framework that effectively incorporates LLMs to augment existing numerical approaches for the intervention targeting in causal discovery. Across $4$ realistic benchmark scales, \ours demonstrates significant improvements and robustness over existing methods and even surpasses humans, which demonstrates the usefulness of LLMs in assisting with experimental design for scientific discovery.

[Arxiv](https://arxiv.org/abs/2503.01139)