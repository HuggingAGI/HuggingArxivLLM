# # 上下文图转换器：一款小型语言模型设计，提升工程文档信息提取效果

发布时间：2025年08月04日

`RAG` `技术文档` `问答系统`

> Contextual Graph Transformer: A Small Language Model for Enhanced Engineering Document Information Extraction

# 摘要

> # 上下文图变换器（CGT）：技术文档问答的高效解决方案

标准的transformer模型虽然在通用文本处理上表现出色，但在复杂技术文档的精细语法和实体关系处理上仍有不足。针对这一挑战，我们提出了上下文图变换器（CGT），一种结合图神经网络（GNNs）和transformers的混合架构，专为技术领域的问题回答设计。

CGT通过构建动态图来处理输入令牌，利用顺序、跳元和语义相似性边进行局部结构学习，随后通过Transformer编码器捕获全局依赖关系。与通用模型不同，技术领域需要更强大的上下文和结构感知能力，而CGT以其参数高效的特性完美胜任。

在检索增强生成（RAG）管道中，CGT表现优异，相比GPT-2，参数减少62.4%的同时准确率提升24.7%。这一优势源于其对结构化交互和语义连贯性的联合建模能力。

通过两阶段训练方法：先在通用文本上预训练，再在领域手册上微调，CGT展现了对技术语言的强大适应性。这使其在实际应用中能够实现更精准的 grounding、实体追踪和增强检索响应。

> Standard transformer-based language models, while powerful for general text, often struggle with the fine-grained syntax and entity relationships in complex technical, engineering documents. To address this, we propose the Contextual Graph Transformer (CGT), a hybrid neural architecture that combines Graph Neural Networks (GNNs) and Transformers for domain-specific question answering. CGT constructs a dynamic graph over input tokens using sequential, skip-gram, and semantic similarity edges, which is processed by GATv2Conv layers for local structure learning. These enriched embeddings are then passed to a Transformer encoder to capture global dependencies. Unlike generic large models, technical domains often require specialized language models with stronger contextualization and structure awareness. CGT offers a parameter-efficient solution for such use cases. Integrated into a Retrieval-Augmented Generation (RAG) pipeline, CGT outperforms baselines like GPT-2 and BERT, achieving 24.7% higher accuracy than GPT-2 with 62.4% fewer parameters. This gain stems from CGTs ability to jointly model structural token interactions and long-range semantic coherence. The model is trained from scratch using a two-phase approach: pretraining on general text followed by fine-tuning on domain-specific manuals. This highlights CGTs adaptability to technical language, enabling better grounding, entity tracking, and retrieval-augmented responses in real-world applications.

[Arxiv](https://arxiv.org/abs/2508.02532)