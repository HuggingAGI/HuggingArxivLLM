# HumorReject: 用幽默巧妙解耦LLM安全性与拒绝前缀

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了一种新的数据驱动方法（HumorReject）来提升大型语言模型（LLMs）的安全性，特别是通过幽默作为间接拒绝策略来应对有害指令。这种方法属于对LLM在实际应用中的改进和优化，因此归类为LLM应用。` `人工智能` `网络安全`

> HumorReject: Decoupling LLM Safety from Refusal Prefix via A Little Humor

# 摘要

> 大型语言模型（LLMs）通常依赖显式拒绝前缀来确保安全，但这使其易受前缀注入攻击。我们提出了HumorReject，一种创新的数据驱动方法，通过幽默作为间接拒绝策略，彻底重构了LLM的安全性，使其不再依赖拒绝前缀。HumorReject不会直接拒绝有害指令，而是以情境幽默回应，巧妙化解潜在危险请求，同时保持互动趣味性。该方法有效解决了现有安全机制中的“过度防御”问题，展现出对多种攻击向量的强大防御能力，同时在合法任务上保持了自然流畅的高质量互动。研究表明，数据层面的创新比对齐算法更能从根本上提升LLM的安全性，为开发更具韧性和用户友好的AI系统开辟了新方向。

> Large Language Models (LLMs) commonly rely on explicit refusal prefixes for safety, making them vulnerable to prefix injection attacks. We introduce HumorReject, a novel data-driven approach that fundamentally reimagines LLM safety by decoupling it from refusal prefixes through the use of humor as an indirect refusal strategy. Rather than explicitly rejecting harmful instructions, HumorReject responds with contextually appropriate humor that naturally defuses potentially dangerous requests while maintaining engaging interactions. Our approach effectively addresses the common "over-defense" issues in existing safety mechanisms, demonstrating superior robustness against various attack vectors while preserving natural and high-quality interactions on legitimate tasks. Our findings suggest that innovations at the data level are even more fundamental than the alignment algorithm itself in achieving effective LLM safety, opening new directions for developing more resilient and user-friendly AI systems.

[Arxiv](https://arxiv.org/abs/2501.13677)