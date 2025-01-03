# TrustRAG: 提升RAG的稳健性与可信赖性

发布时间：2025年01月01日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统，并提出了一个名为TrustRAG的框架，用于增强RAG系统对语料库中毒攻击的防御能力。论文的核心内容围绕如何通过外部知识源提升LLM的生成能力，并解决RAG系统中的安全问题。因此，这篇论文应归类为RAG。` `信息安全`

> TrustRAG: Enhancing Robustness and Trustworthiness in RAG

# 摘要

> # 摘要
检索增强生成（RAG）系统通过整合外部知识源，显著提升了大型语言模型（LLMs）生成与用户查询相关且准确的响应的能力。然而，这些系统仍面临语料库中毒攻击的威胁，攻击者通过注入恶意内容大幅削弱LLM的性能。为此，我们提出了TrustRAG，一个强大的框架，能够在内容进入语言模型前系统过滤受损和不相关的内容。TrustRAG采用两阶段防御机制：首先，利用K-means聚类基于语义嵌入识别检索文档中的潜在攻击模式，有效隔离可疑内容；其次，通过余弦相似度和ROUGE指标检测恶意文档，并通过自评估过程解决模型内部知识与外部信息之间的差异。TrustRAG作为即插即用、无需训练的模块，可与任何语言模型无缝集成，无论是开源还是闭源，在保持高上下文相关性的同时，显著增强了对攻击的防御能力。通过大量实验验证，我们证明TrustRAG在检索准确性、效率和攻击抵抗力方面均优于现有方法，适用于多种模型架构和数据集。TrustRAG已作为开源软件发布在url{https://github.com/HuichiZhou/TrustRAG}。

> Retrieval-Augmented Generation (RAG) systems enhance large language models (LLMs) by integrating external knowledge sources, enabling more accurate and contextually relevant responses tailored to user queries. However, these systems remain vulnerable to corpus poisoning attacks that can significantly degrade LLM performance through the injection of malicious content. To address these challenges, we propose TrustRAG, a robust framework that systematically filters compromised and irrelevant content before it reaches the language model. Our approach implements a two-stage defense mechanism: first, it employs K-means clustering to identify potential attack patterns in retrieved documents based on their semantic embeddings, effectively isolating suspicious content. Second, it leverages cosine similarity and ROUGE metrics to detect malicious documents while resolving discrepancies between the model's internal knowledge and external information through a self-assessment process. TrustRAG functions as a plug-and-play, training-free module that integrates seamlessly with any language model, whether open or closed-source, maintaining high contextual relevance while strengthening defenses against attacks. Through extensive experimental validation, we demonstrate that TrustRAG delivers substantial improvements in retrieval accuracy, efficiency, and attack resistance compared to existing approaches across multiple model architectures and datasets. We have made TrustRAG available as open-source software at \url{https://github.com/HuichiZhou/TrustRAG}.

[Arxiv](https://arxiv.org/abs/2501.00879)