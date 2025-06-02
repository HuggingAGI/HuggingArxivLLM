# mRAG：探索多模态增强生成的设计领域

发布时间：2025年05月29日

`Agent` `多模态` `生成技术`

> mRAG: Elucidating the Design Space of Multi-modal Retrieval-Augmented Generation

# 摘要

> 大型视觉-语言模型 (LVLMs) 在视觉问答、视觉定位和复杂推理等多模态任务中取得了显著进展。然而，它们仍受限于静态训练数据、易受幻觉影响，以及无法根据最新外部证据验证声明，这影响了它们在动态现实世界应用中的性能。检索增强生成 (RAG) 通过允许 LVLMs 通过检索机制访问大规模知识数据库，提供了一个实用的解决方案，将模型输出扎根于事实性和上下文相关的数据中。本文中，我们对 LVLMs 的多模态 RAG 管道进行了首次系统性分解，研究了 (1) 检索阶段的模态配置和检索策略，(2) 重新排序阶段的缓解位置偏见和提高检索证据相关性的策略，以及 (3) 生成阶段如何将检索到的候选者最佳整合到最终生成过程中。最后，我们探索了一种通过自我反思将重新排序和生成整合在一起的统一智能体框架，使 LVLMs 能够动态选择相关证据并抑制不相关上下文。我们对 LVLMs 的 RAG 进行的全栈探索带来了实质性的见解，无需微调，平均性能提升了 5%。

> Large Vision-Language Models (LVLMs) have made remarkable strides in multimodal tasks such as visual question answering, visual grounding, and complex reasoning. However, they remain limited by static training data, susceptibility to hallucinations, and inability to verify claims against up-to-date, external evidence, compromising their performance in dynamic real-world applications. Retrieval-Augmented Generation (RAG) offers a practical solution to mitigate these challenges by allowing the LVLMs to access large-scale knowledge databases via retrieval mechanisms, thereby grounding model outputs in factual, contextually relevant information. Here in this paper, we conduct the first systematic dissection of the multimodal RAG pipeline for LVLMs, explicitly investigating (1) the retrieval phase: on the modality configurations and retrieval strategies, (2) the re-ranking stage: on strategies to mitigate positional biases and improve the relevance of retrieved evidence, and (3) the generation phase: we further investigate how to best integrate retrieved candidates into the final generation process. Finally, we extend to explore a unified agentic framework that integrates re-ranking and generation through self-reflection, enabling LVLMs to select relevant evidence and suppress irrelevant context dynamically. Our full-stack exploration of RAG for LVLMs yields substantial insights, resulting in an average performance boost of 5% without any fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.24073)