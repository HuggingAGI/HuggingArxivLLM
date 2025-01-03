# KaLM-Embedding: 优质数据铸就更强嵌入模型

发布时间：2025年01月01日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）中的一个关键组件——嵌入模型，并提出了一个新的通用多语言嵌入模型KaLM-Embedding。论文的重点在于如何通过改进训练数据质量和模型架构来提升嵌入模型的性能，以支持RAG系统的应用。因此，这篇论文应归类为RAG。` `多语言嵌入`

> KaLM-Embedding: Superior Training Data Brings A Stronger Embedding Model

# 摘要

> 随着检索增强生成在大型语言模型中的广泛应用，嵌入模型的重要性日益凸显。尽管通用嵌入模型层出不穷，但以往研究常忽视训练数据质量的关键影响。本文提出KaLM-Embedding，一种通用多语言嵌入模型，利用大量更纯净、多样且领域特定的训练数据。我们采用多项关键技术提升模型性能：（1）基于角色的合成数据，从LLMs中提炼多样化示例；（2）排名一致性过滤，剔除信息量低的样本；（3）半同质任务批量采样，提升训练效率。与传统BERT架构不同，我们选用Qwen2-0.5B作为预训练模型，使自回归语言模型更适应通用嵌入任务。MTEB基准的多语言评估显示，我们的模型在同等规模下表现优异，为参数少于10亿的多语言嵌入模型树立了新标杆。

> As retrieval-augmented generation prevails in large language models, embedding models are becoming increasingly crucial. Despite the growing number of general embedding models, prior work often overlooks the critical role of training data quality. In this work, we introduce KaLM-Embedding, a general multilingual embedding model that leverages a large quantity of cleaner, more diverse, and domain-specific training data. Our model has been trained with key techniques proven to enhance performance: (1) persona-based synthetic data to create diversified examples distilled from LLMs, (2) ranking consistency filtering to remove less informative samples, and (3) semi-homogeneous task batch sampling to improve training efficacy. Departing from traditional BERT-like architectures, we adopt Qwen2-0.5B as the pre-trained model, facilitating the adaptation of auto-regressive language models for general embedding tasks. Extensive evaluations of the MTEB benchmark across multiple languages show that our model outperforms others of comparable size, setting a new standard for multilingual embedding models with <1B parameters.

[Arxiv](https://arxiv.org/abs/2501.01028)