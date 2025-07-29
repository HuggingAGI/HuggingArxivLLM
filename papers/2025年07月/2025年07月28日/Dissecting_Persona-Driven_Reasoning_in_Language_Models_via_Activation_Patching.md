# # 分解语言模型中的基于角色推理：通过激活补丁技术
通过激活补丁技术解构语言模型中基于角色的推理机制

发布时间：2025年07月28日

`LLM理论` `人工智能`

> Dissecting Persona-Driven Reasoning in Language Models via Activation Patching

# 摘要

> 大型语言模型（LLMs）在扮演各种角色方面展现出惊人的灵活性。本研究旨在探讨赋予模型特定角色如何影响其在客观任务中的推理能力。借助激活补丁技术，我们首次深入探究了模型如何编码与角色相关的特定信息。研究发现，早期的多层感知机（MLP）层不仅关注输入的句法结构，还深入处理其语义内容。这些层将角色标记转化为更丰富的表示形式，随后由中间的多头注意力（MHA）层利用这些表示来塑造模型的输出。此外，我们还发现某些特定的注意力头对基于种族和颜色的身份信息表现出过度关注。

> Large language models (LLMs) exhibit remarkable versatility in adopting diverse personas. In this study, we examine how assigning a persona influences a model's reasoning on an objective task. Using activation patching, we take a first step toward understanding how key components of the model encode persona-specific information. Our findings reveal that the early Multi-Layer Perceptron (MLP) layers attend not only to the syntactic structure of the input but also process its semantic content. These layers transform persona tokens into richer representations, which are then used by the middle Multi-Head Attention (MHA) layers to shape the model's output. Additionally, we identify specific attention heads that disproportionately attend to racial and color-based identities.

[Arxiv](https://arxiv.org/abs/2507.20936)