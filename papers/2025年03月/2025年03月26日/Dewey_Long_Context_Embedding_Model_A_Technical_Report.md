# # Dewey长上下文嵌入模型：技术报告

发布时间：2025年03月26日

`RAG` `RAG系统` `生成式AI`

> Dewey Long Context Embedding Model: A Technical Report

# 摘要

> # 技术报告
这份报告介绍了开源 dewey_en_beta 嵌入模型的训练方法和评估结果。随着检索增强生成（RAG）系统需求的增加以及大型语言模型（LLMs）上下文窗口能力的扩展，传统嵌入模型面临严峻挑战。现有方法在处理超出典型序列长度限制的文档时，往往难以保持语义连贯性，对知识密集型应用中的检索性能造成重大影响。

本文提出 dewey_en_beta，一种新型文本嵌入模型，在 MTEB（Eng, v2）和 LongEmbed 基准测试中表现优异，同时支持 128K 令牌序列。我们的技术贡献核心在于分块对齐训练，这是一种创新方法，通过蒸馏技术同时生成局部块嵌入和全局文档级别表示。有关模型发布的信息，请访问 https://huggingface.co/infgrad/dewey_en_beta。


> This technical report presents the training methodology and evaluation results of the open-source dewey_en_beta embedding model. The increasing demand for retrieval-augmented generation (RAG) systems and the expanding context window capabilities of large language models (LLMs) have created critical challenges for conventional embedding models. Current approaches often struggle to maintain semantic coherence when processing documents exceeding typical sequence length limitations, significantly impacting retrieval performance in knowledge-intensive applications. This paper presents dewey_en_beta, a novel text embedding model that achieves excellent performance on MTEB (Eng, v2) and LongEmbed benchmark while supporting 128K token sequences. Our technical contribution centers on chunk alignment training, an innovative methodology that enables the simultaneous generation of localized chunk embeddings and global document-level representations through distillation. Information regarding the model release can be found at https://huggingface.co/infgrad/dewey_en_beta.

[Arxiv](https://arxiv.org/abs/2503.20376)