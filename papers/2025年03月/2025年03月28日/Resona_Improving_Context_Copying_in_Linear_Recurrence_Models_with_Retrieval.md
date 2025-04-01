# Resona：通过检索优化线性递归模型中的上下文复制

发布时间：2025年03月28日

`LLM理论` `人工智能`

> Resona: Improving Context Copying in Linear Recurrence Models with Retrieval

# 摘要

> 大型语言模型 (LLM) 研究领域正经历一场变革，研究者们正将目光投向新型架构，试图打破 Transformer 模型的长期主导地位。线性递归模型凭借其高效的计算能力，展现出成为 Transformer 竞争对手的潜力。然而，这些模型在上下文学习等需要从上下文中提取信息的任务上，仍与 Transformer 存在明显差距。为解决这一问题，我们提出了 __Resona__，一个简单且可扩展的框架，旨在通过检索机制增强线性递归模型。__Resona__ 赋予模型从输入上下文中检索并整合信息的能力，使其能够灵活应对各种任务需求。实验结果表明，经过 __Resona__ 增强的模型在多种合成与真实世界自然语言任务中均表现出显著性能提升，充分证明了其作为通用解决方案，在提升线性递归 LLM 的上下文学习和语言建模能力方面具有巨大潜力。

> Recent shifts in the space of large language model (LLM) research have shown an increasing focus on novel architectures to compete with prototypical Transformer-based models that have long dominated this space. Linear recurrent models have proven to be a viable competitor due to their computational efficiency. However, such models still demonstrate a sizable gap compared to Transformers in terms of in-context learning among other tasks that require recalling information from a context. In this work, we introduce __Resona__, a simple and scalable framework for augmenting linear recurrent models with retrieval. __Resona__~augments models with the ability to integrate retrieved information from the provided input context, enabling tailored behavior to diverse task requirements. Experiments on a variety of linear recurrent models demonstrate that __Resona__-augmented models observe significant performance gains on a variety of synthetic as well as real-world natural language tasks, highlighting its ability to act as a general purpose method to improve the in-context learning and language modeling abilities of linear recurrent LLMs.

[Arxiv](https://arxiv.org/abs/2503.22913)