# 语言手术：多语言大型语言模型的解构与重构

发布时间：2025年06月14日

`LLM理论` `跨语言技术`

> Language Surgery in Multilingual Large Language Models

# 摘要

> 大型语言模型 (LLMs) 凭借其跨任务和跨语言的卓越泛化能力，正在彻底改变自然语言处理领域。本文聚焦于 LLMs 中自然浮现的表征对齐现象，特别是在中间层的表现，并深入探讨其在区分语言特定信息与通用语言信息中的作用。我们通过实证研究确认了这一对齐现象的存在，分析了其行为特征并与显式设计的对齐模型进行了对比，同时展示了其在不降解语义的前提下进行语言特定操作的潜力。基于这些发现，我们提出了一种创新方法——推理时语言控制 (ITLC)，该方法通过潜在注入技术实现对 LLMs 的精确跨语言控制，并有效缓解语言混淆问题。实验结果表明，ITLC 在跨语言控制方面表现出色，同时保持了目标语言的语义完整性。此外，我们还证实了其在解决当前大规模 LLMs 中普遍存在的跨语言语言混淆问题方面的有效性，这一问题往往导致语言生成结果不一致。这项研究不仅深化了我们对 LLMs 表征对齐机制的理解，更为提升其跨语言性能提供了切实可行的解决方案。

> Large Language Models (LLMs) have demonstrated remarkable generalization capabilities across tasks and languages, revolutionizing natural language processing. This paper investigates the naturally emerging representation alignment in LLMs, particularly in the middle layers, and its implications for disentangling language-specific and language-agnostic information. We empirically confirm the existence of this alignment, analyze its behavior in comparison to explicitly designed alignment models, and demonstrate its potential for language-specific manipulation without semantic degradation. Building on these findings, we propose Inference-Time Language Control (ITLC), a novel method that leverages latent injection to enable precise cross-lingual language control and mitigate language confusion in LLMs. Our experiments highlight ITLC's strong cross-lingual control capabilities while preserving semantic integrity in target languages. Furthermore, we demonstrate its effectiveness in alleviating the cross-lingual language confusion problem, which persists even in current large-scale LLMs, leading to inconsistent language generation. This work advances our understanding of representation alignment in LLMs and introduces a practical solution for enhancing their cross-lingual performance.

[Arxiv](https://arxiv.org/abs/2506.12450)