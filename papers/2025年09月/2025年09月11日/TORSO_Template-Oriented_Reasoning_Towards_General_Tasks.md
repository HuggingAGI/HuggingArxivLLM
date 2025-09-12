# TORSO：面向通用任务的模板导向推理

发布时间：2025年09月11日

`LLM应用` `基础理论`

> TORSO: Template-Oriented Reasoning Towards General Tasks

# 摘要

> 引导大型语言模型（LLMs）在生成响应时模拟人类推理，这种方法能让模型逐步解决复杂问题并实现卓越性能，已被证明十分有效。但目前多数基于少样本提示生成响应的方法，都严重依赖给定示例，这限制了模型自身推理能力的发挥。此外，为特定任务构建少样本提示不仅成本高，还可能造成不同任务间的不一致性。为此，我们提出了面向模板的推理（TORSO）方法。该方法能激发模型的内在推理能力，使其在各类任务中生成恰当响应，且无需手动设计少样本示例。实验结果显示，TORSO在多个LLM基准测试中均表现优异，且推理过程合理有据。

> The approaches that guide Large Language Models (LLMs) to emulate human reasoning during response generation have emerged as an effective method for enabling them to solve complex problems in a step-by-step manner, thereby achieving superior performance. However, most existing approaches using few-shot prompts to generate responses heavily depend on the provided examples, limiting the utilization of the model's inherent reasoning capabilities. Moreover, constructing task-specific few-shot prompts is often costly and may lead to inconsistencies across different tasks. In this work, we introduce Template-Oriented Reasoning (TORSO), which elicits the model to utilize internal reasoning abilities to generate proper responses across various tasks without the need for manually crafted few-shot examples. Our experimental results demonstrate that TORSO achieves strong performance on diverse LLMs benchmarks with reasonable rationales.

[Arxiv](https://arxiv.org/abs/2509.09448)