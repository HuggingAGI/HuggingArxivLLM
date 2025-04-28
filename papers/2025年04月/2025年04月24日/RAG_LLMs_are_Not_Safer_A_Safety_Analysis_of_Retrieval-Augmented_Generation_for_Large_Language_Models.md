# RAG LLMs 并非更安全：大型语言模型检索增强生成的安全性分析

发布时间：2025年04月24日

`RAG` `人工智能安全` `模型安全`

> RAG LLMs are Not Safer: A Safety Analysis of Retrieval-Augmented Generation for Large Language Models

# 摘要

> 保障大型语言模型（LLMs）安全的方法包括安全微调、评估和红队测试。然而，尽管检索增强生成（RAG）框架被广泛应用，但目前的人工智能安全研究主要集中在标准LLMs上，这意味着我们对RAG使用场景如何改变模型安全特性知之甚少。我们对11种LLMs的RAG和非RAG框架进行了详细对比分析。发现RAG可能会降低模型的安全性并改变其安全特性。我们深入探究了这种变化的原因，发现即使将安全模型与安全文档组合，也可能产生不安全的输出。此外，我们评估了一些现有的红队测试方法在RAG环境下的效果，发现它们的效力显著低于在非RAG环境中的表现。本研究强调了针对RAG LLMs专门开发安全研究和红队测试方法的必要性。

> Efforts to ensure the safety of large language models (LLMs) include safety fine-tuning, evaluation, and red teaming. However, despite the widespread use of the Retrieval-Augmented Generation (RAG) framework, AI safety work focuses on standard LLMs, which means we know little about how RAG use cases change a model's safety profile. We conduct a detailed comparative analysis of RAG and non-RAG frameworks with eleven LLMs. We find that RAG can make models less safe and change their safety profile. We explore the causes of this change and find that even combinations of safe models with safe documents can cause unsafe generations. In addition, we evaluate some existing red teaming methods for RAG settings and show that they are less effective than when used for non-RAG settings. Our work highlights the need for safety research and red-teaming methods specifically tailored for RAG LLMs.

[Arxiv](https://arxiv.org/abs/2504.18041)