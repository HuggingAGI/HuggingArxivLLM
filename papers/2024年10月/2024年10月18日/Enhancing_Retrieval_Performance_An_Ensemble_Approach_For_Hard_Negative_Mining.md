# 提升检索性能：硬负样本挖掘的集成策略

发布时间：2024年10月18日

`RAG

理由：该论文摘要主要讨论了检索和排名模型在信息检索中的应用，特别是如何通过硬负例采样技术提升交叉编码器模型的性能。摘要中提到，这种技术可以增强检索增强生成（RAG）和推理与行动代理（ReAct）等先进LLM系统的性能。因此，该论文的核心内容与RAG（检索增强生成）密切相关，故将其分类为RAG。` `信息检索` `企业应用`

> Enhancing Retrieval Performance: An Ensemble Approach For Hard Negative Mining

# 摘要

> # 摘要
排名始终是信息检索研究的核心。检索和排名模型支撑着众多应用，如网络搜索、开放领域问答、企业领域问答以及文本推荐系统。这些模型通常基于二元相关性分配的三元组进行训练，包含一个正例和一个负例段落。然而，实际应用中需要对相关性有更精细的理解，尤其是在对大量潜在相关段落进行重新排名时。虽然通过用户反馈（如点击或印象）收集正例相对容易，但从数百万甚至数十亿文档中筛选合适的负例对则更具挑战性。为了保持模型的高质量，通常需要生成大量负例对。已有文献提出了多种方法来解决从大规模语料库中选择合适负例对的问题。本研究重点探讨了硬负例在交叉编码器模型训练中的关键作用，特别是解释了硬负例采样相比随机采样带来的性能提升。我们开发了一种高效的硬负例挖掘技术，用于在企业数据集上训练交叉编码器重新排名模型，该数据集具有特定领域的上下文。我们提供了一种新颖的视角来增强检索模型，最终提升了如检索增强生成（RAG）和推理与行动代理（ReAct）等先进LLM系统的性能。研究表明，通过交叉编码器同时学习相似性和不相似性，能够显著提升检索系统的表现。

> Ranking consistently emerges as a primary focus in information retrieval research. Retrieval and ranking models serve as the foundation for numerous applications, including web search, open domain QA, enterprise domain QA, and text-based recommender systems. Typically, these models undergo training on triplets consisting of binary relevance assignments, comprising one positive and one negative passage. However, their utilization involves a context where a significantly more nuanced understanding of relevance is necessary, especially when re-ranking a large pool of potentially relevant passages. Although collecting positive examples through user feedback like impressions or clicks is straightforward, identifying suitable negative pairs from a vast pool of possibly millions or even billions of documents possess a greater challenge. Generating a substantial number of negative pairs is often necessary to maintain the high quality of the model. Several approaches have been suggested in literature to tackle the issue of selecting suitable negative pairs from an extensive corpus. This study focuses on explaining the crucial role of hard negatives in the training process of cross-encoder models, specifically aiming to explain the performance gains observed with hard negative sampling compared to random sampling. We have developed a robust hard negative mining technique for efficient training of cross-encoder re-rank models on an enterprise dataset which has domain specific context. We provide a novel perspective to enhance retrieval models, ultimately influencing the performance of advanced LLM systems like Retrieval-Augmented Generation (RAG) and Reasoning and Action Agents (ReAct). The proposed approach demonstrates that learning both similarity and dissimilarity simultaneously with cross-encoders improves performance of retrieval systems.

[Arxiv](https://arxiv.org/abs/2411.02404)