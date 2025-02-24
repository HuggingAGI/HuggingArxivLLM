# # 链式排序：提升边缘设备中大型语言模型的领域增强生成能力

发布时间：2025年02月20日

`RAG` `专业领域` `边缘设备`

> Chain-of-Rank: Enhancing Large Language Models for Domain-Specific RAG in Edge Device

# 摘要

> 基于大型语言模型（LLMs）的检索增强生成（RAG）在专业领域中尤其有价值，这些领域对精度要求极高。为了使LLMs更专业化地应用于目标领域，近期开发了一种领域特定的RAG方法，通过微调使LLM能够尽早访问目标领域。这种领域特定的RAG在资源受限的环境中（如边缘设备）更有意义，因为它们需要仅使用小型LLMs可靠地执行特定任务（例如个性化）。尽管领域特定的RAG在这一点上与边缘设备高度契合，但它通常依赖于广泛使用的推理技术，如思维链（CoT）。推理步骤有助于理解给定的外部知识，但计算成本高昂，且小型LLMs难以掌握这一过程。针对这一问题，我们提出了Chain of Rank（CoR），将关注点从复杂的长篇推理转向对输入外部文档可靠性的简单排序。CoR降低了计算复杂度，同时保持了高准确性，使其特别适合资源受限的环境。我们在基准测试中达到了最先进（SOTA）的结果，并对其有效性进行了分析。

> Retrieval-augmented generation (RAG) with large language models (LLMs) is especially valuable in specialized domains, where precision is critical. To more specialize the LLMs into a target domain, domain-specific RAG has recently been developed by allowing the LLM to access the target domain early via finetuning. The domain-specific RAG makes more sense in resource-constrained environments like edge devices, as they should perform a specific task (e.g. personalization) reliably using only small-scale LLMs. While the domain-specific RAG is well-aligned with edge devices in this respect, it often relies on widely-used reasoning techniques like chain-of-thought (CoT). The reasoning step is useful to understand the given external knowledge, and yet it is computationally expensive and difficult for small-scale LLMs to learn it. Tackling this, we propose the Chain of Rank (CoR) which shifts the focus from intricate lengthy reasoning to simple ranking of the reliability of input external documents. Then, CoR reduces computational complexity while maintaining high accuracy, making it particularly suited for resource-constrained environments. We attain the state-of-the-art (SOTA) results in benchmarks, and analyze its efficacy.

[Arxiv](https://arxiv.org/abs/2502.15134)