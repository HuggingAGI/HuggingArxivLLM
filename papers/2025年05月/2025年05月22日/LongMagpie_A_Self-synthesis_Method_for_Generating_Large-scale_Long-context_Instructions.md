# LongMagpie: 生成大规模长上下文指令的自合成方法

发布时间：2025年05月22日

`LLM应用

理由：这篇论文主要讨论了如何通过自动生成高质量的长上下文指令数据来改进大型语言模型的对齐过程。LongMagpie框架的应用直接提升了LLM在处理长上下文任务中的性能，属于LLM的实际应用层面。` `人工智能` `数据处理`

> LongMagpie: A Self-synthesis Method for Generating Large-scale Long-context Instructions

# 摘要

> 长上下文大型语言模型（LLMs）的对齐需要高质量的长上下文指令数据。尽管Qwen和Llama等模型已公开发布，但它们的长上下文指令数据仍属专有。人工标注成本高昂且困难，而基于模板的合成方法在规模、多样性和质量上存在局限。我们提出了LongMagpie，一个自合成框架，能够自动生成大规模长上下文指令数据。我们的核心发现是，当对齐的长上下文LLMs在呈现一个文档后，遇到特殊标记并随后出现用户回合时，会自回归生成上下文相关的查询。通过收集这些文档-查询对和模型的响应，LongMagpie无需人工干预即可生成高质量的指令。在HELMET、RULER和Longbench v2上的实验表明，LongMagpie在长上下文任务中表现出色，同时在短上下文任务中也保持了竞争力，证明了它是一种开放、多样且可扩展的长上下文指令数据合成的简单有效方法。

> High-quality long-context instruction data is essential for aligning long-context large language models (LLMs). Despite the public release of models like Qwen and Llama, their long-context instruction data remains proprietary. Human annotation is costly and challenging, while template-based synthesis methods limit scale, diversity, and quality. We introduce LongMagpie, a self-synthesis framework that automatically generates large-scale long-context instruction data. Our key insight is that aligned long-context LLMs, when presented with a document followed by special tokens preceding a user turn, auto-regressively generate contextually relevant queries. By harvesting these document-query pairs and the model's responses, LongMagpie produces high-quality instructions without human effort. Experiments on HELMET, RULER, and Longbench v2 demonstrate that LongMagpie achieves leading performance on long-context tasks while maintaining competitive performance on short-context tasks, establishing it as a simple and effective approach for open, diverse, and scalable long-context instruction data synthesis.

[Arxiv](https://arxiv.org/abs/2505.17134)