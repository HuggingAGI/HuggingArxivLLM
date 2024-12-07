# 基于非结构化知识的检索增强型机器翻译

发布时间：2024年12月05日

`RAG` `机器翻译`

> Retrieval-Augmented Machine Translation with Unstructured Knowledge

# 摘要

> 检索增强生成（RAG）引入额外信息以强化大型语言模型（LLMs）。在机器翻译（MT）领域，以往工作通常从配对的 MT 语料库中检索上下文示例，或从知识图谱中获取特定领域知识，来增强模型的 MT 能力。然而，大量世界知识是以非结构化文档形式组织的，且在不同语言间可能未完全配对。在本文中，我们研究利用非结构化文档的检索增强型 MT。具体而言，我们构建了 RAGtrans，这是首个用于训练和评估 LLMs 检索增强型 MT 能力的基准。RAGtrans 包含通过 GPT-4o 和人类翻译员收集的 79K 个 MT 样本。此外，还提供了不同语言的文档，为这些样本提供知识。基于 RAGtrans，我们进一步提出一种多任务训练方法，教导 LLMs 在翻译时如何使用多语言文档中的信息。该方法利用现有的多语言语料库创建辅助训练目标，无需额外标注要求。大量实验表明，该方法使 LLMs 的 BLEU 分数提升了 1.58 - 3.09，COMET 分数提升了 1.00 - 2.03。

> Retrieval-augmented generation (RAG) introduces additional information to enhance large language models (LLMs). In machine translation (MT), previous work typically retrieves in-context examples from paired MT corpora, or domain-specific knowledge from knowledge graphs, to enhance models' MT ability. However, a large amount of world knowledge is organized in unstructured documents, and might not be fully paired across different languages. In this paper, we study retrieval-augmented MT using unstructured documents. Specifically, we build RAGtrans, the first benchmark to train and evaluate LLMs' retrieval-augmented MT ability. RAGtrans contains 79K MT samples collected via GPT-4o and human translators. Besides, documents from different languages are also provided to supply the knowledge to these samples. Based on RAGtrans, we further propose a multi-task training method to teach LLMs how to use information from multilingual documents during their translation. The method uses existing multilingual corpora to create auxiliary training objectives without additional labeling requirements. Extensive experiments show that the method improves LLMs by 1.58-3.09 BLEU and 1.00-2.03 COMET scores.

[Arxiv](https://arxiv.org/abs/2412.04342)