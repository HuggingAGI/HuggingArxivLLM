# # 大型语言模型内部推理的潜在记忆方法：超越文字

发布时间：2025年02月28日

`LLM理论

摘要讨论了大型语言模型（LLMs）的内部推理机制，提出了一种整合隐性心理表征和记忆模块的框架，以提升模型的推理效率和效果。这属于对模型理论和机制的研究，因此归类为LLM理论。` `人工智能`

> Beyond Words: A Latent Memory Approach to Internal Reasoning in LLMs

# 摘要

> 大型语言模型（LLMs）的最新进展让链式思维（CoT）范式风靡一时，该范式使模型能够以自然语言生成明确的推理步骤。虽然这种方法提升了可解释性并便于外部审核，但它可能并非内部推理最高效的手段。人类认知则依赖于隐性的心理表征，能够调用过去的感觉和情景信息，而无需完全转化为语言。本文提出了一种将隐性心理表征整合进LLMs内部推理过程的框架。初步实验表明，与普通GPT基线相比，将隐性记忆模块（IMM）整合到简单GPT模型中，最终训练损失降低了35%到57%。在此方法中添加一个显式的可解释性通道（例如链式思维解码器）易于实现。我们概述了理论基础，提出了扩展记忆模块的技术机制，并探讨了这些思路如何带来更高效、更稳健的推理能力，以及未来可能实现显式审核的可选扩展方向。

> Recent advances in large language models (LLMs) have popularized the chain-of-thought (CoT) paradigm, in which models produce explicit reasoning steps in natural language. Although this approach improves interpretability and facilitates external auditing, it may not represent the most computationally efficient method for internal reasoning. In contrast, human cognition relies on implicit mental representations that recall past sensory and episodic information without requiring complete verbalization. In this paper, we propose a framework that integrates implicit mental representations into the internal reasoning processes of LLMs. Preliminary experiments indicate that incorporating an Implicit Memory Module (IMM) into a simple GPT model yields a reduction of between 35% and 57% in final training loss compared to a regular GPT baseline. The addition of an explicit interpretability channel (e.g., a chain-of-thought decoder) is straightforward to implement within this approach. We outline theoretical foundations, propose technical mechanisms to scale the memory module, and discuss how these ideas may lead to more efficient and robust reasoning, with optional future extensions for explicit auditability.

[Arxiv](https://arxiv.org/abs/2502.21030)