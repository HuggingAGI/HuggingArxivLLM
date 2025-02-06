# 基于微调与检索增强生成技术的医疗保险对话AI系统

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在医患对话场景中的应用，特别是对比了LoRA微调和RAG框架在多个混合医学领域数据集上的表现。研究重点在于评估模型的语言质量、事实准确性、对医学指南的遵循度以及人类评估等方面。这些内容都属于LLM在实际应用中的表现和优化，因此归类为“LLM应用”。`

> Conversation AI Dialog for Medicare powered by Finetuning and Retrieval Augmented Generation

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现出色，尤其是在对话生成方面。本研究聚焦于医患对话场景，对比分析了两种关键技术：LoRA微调和RAG框架，并使用了多个混合医学领域的数据集。我们评估了Llama-2、GPT和LSTM三个前沿模型的表现，重点关注语言质量（如困惑度、BLEU分数）、事实准确性（基于医学知识库的核查）、对医学指南的遵循度以及人类评估（如连贯性、同理心、安全性）。研究结果揭示了每种方法的优劣，为它们在医疗领域的应用提供了参考。此外，我们还探讨了模型在处理多样化患者查询时的表现，从一般健康问题到特定病症，并研究了领域知识整合对模型性能的提升潜力，强调了数据增强和检索策略的重要性。

> Large language models (LLMs) have shown impressive capabilities in natural language processing tasks, including dialogue generation. This research aims to conduct a novel comparative analysis of two prominent techniques, fine-tuning with LoRA (Low-Rank Adaptation) and the Retrieval-Augmented Generation (RAG) framework, in the context of doctor-patient chat conversations with multiple datasets of mixed medical domains. The analysis involves three state-of-the-art models: Llama-2, GPT, and the LSTM model. Employing real-world doctor-patient dialogues, we comprehensively evaluate the performance of models, assessing key metrics such as language quality (perplexity, BLEU score), factual accuracy (fact-checking against medical knowledge bases), adherence to medical guidelines, and overall human judgments (coherence, empathy, safety). The findings provide insights into the strengths and limitations of each approach, shedding light on their suitability for healthcare applications. Furthermore, the research investigates the robustness of the models in handling diverse patient queries, ranging from general health inquiries to specific medical conditions. The impact of domain-specific knowledge integration is also explored, highlighting the potential for enhancing LLM performance through targeted data augmentation and retrieval strategies.

[Arxiv](https://arxiv.org/abs/2502.02249)