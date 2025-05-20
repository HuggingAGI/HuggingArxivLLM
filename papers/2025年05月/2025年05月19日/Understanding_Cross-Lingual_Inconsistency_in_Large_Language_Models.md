# 理解大型语言模型中的跨语言不一致性

发布时间：2025年05月19日

`LLM理论` `人工智能`

> Understanding Cross-Lingual Inconsistency in Large Language Models

# 摘要

> 大型语言模型（LLMs）虽然具备跨语言迁移的能力，但面对不同语言表达的相同查询时，输出往往不一致。为了探究语言模型如何实现跨语言知识迁移，我们借助logit lens工具，揭示了LLMs在解答多语言多选推理问题时的内在推理机制。研究发现，LLMs预测结果不一致且准确率较低，根本原因在于它们各自依赖于特定语言的子空间，而非在一个统一的语义空间中运作。尽管更大规模的模型展现出更强的多语言能力，但其隐藏状态更易与共享表示脱节，不过它们在跨语言知识检索方面表现更佳。最终，我们发现通过引导模型的潜在处理向共享语义空间靠拢，能够有效调节知识共享。强化共享空间的利用显著提升了模型的多语言推理性能，这得益于更高效的跨语言知识转移以及与英语输出的一致性提升。


> Large language models (LLMs) are demonstrably capable of cross-lingual transfer, but can produce inconsistent output when prompted with the same queries written in different languages. To understand how language models are able to generalize knowledge from one language to the others, we apply the logit lens to interpret the implicit steps taken by LLMs to solve multilingual multi-choice reasoning questions. We find LLMs predict inconsistently and are less accurate because they rely on subspaces of individual languages, rather than working in a shared semantic space. While larger models are more multilingual, we show their hidden states are more likely to dissociate from the shared representation compared to smaller models, but are nevertheless more capable of retrieving knowledge embedded across different languages. Finally, we demonstrate that knowledge sharing can be modulated by steering the models' latent processing towards the shared semantic space. We find reinforcing utilization of the shared space improves the models' multilingual reasoning performance, as a result of more knowledge transfer from, and better output consistency with English.

[Arxiv](https://arxiv.org/abs/2505.13141)