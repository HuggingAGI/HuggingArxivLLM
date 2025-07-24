# # 各取所需：探索RAG中的最优嵌入
在RAG（检索增强生成）中，每种模型都有其独特的嵌入方式。本研究旨在深入探索不同嵌入方法对RAG性能的影响，最终找到最适合特定任务的嵌入策略。

发布时间：2025年07月23日

`RAG` `信息检索`

> Each to Their Own: Exploring the Optimal Embedding in RAG

# 摘要

> 最近，随着大型语言模型（LLMs）对各领域的深远影响，如何将最新信息整合到LLMs中或添加外部知识以构建特定领域模型的方法受到了广泛关注。检索增强生成（RAG）作为一种推理时的扩展方法，因其低成本和参数调优的低门槛而备受瞩目。然而，由于训练数据和模型架构的异质性，RAG中使用的变体嵌入模型在不同领域表现出不同的优势，通常导致不同的相似度计算结果，进而影响LLMs的回答质量。为了解决这个问题，我们提出并研究了两种方法，通过结合多个嵌入模型的优势来增强RAG，分别命名为混合嵌入RAG和自信RAG。混合嵌入RAG简单地根据标准化相似度对多个嵌入模型的检索结果进行排序和选择，但未能超越原版RAG。相比之下，自信RAG使用不同的嵌入模型多次生成回答，然后选择置信度最高的回答，与原版LLMs和RAG相比，分别平均提升了约10%和5%。在不同LLMs和嵌入模型上的一致结果表明，自信RAG是一个适用于各种领域的高效即插即用方法。我们将在发表后开源我们的代码。

> Recently, as Large Language Models (LLMs) have fundamentally impacted various fields, the methods for incorporating up-to-date information into LLMs or adding external knowledge to construct domain-specific models have garnered wide attention. Retrieval-Augmented Generation (RAG), serving as an inference-time scaling method, is notable for its low cost and minimal effort for parameter tuning. However, due to heterogeneous training data and model architecture, the variant embedding models used in RAG exhibit different benefits across various areas, often leading to different similarity calculation results and, consequently, varying response quality from LLMs. To address this problem, we propose and examine two approaches to enhance RAG by combining the benefits of multiple embedding models, named Mixture-Embedding RAG and Confident RAG. Mixture-Embedding RAG simply sorts and selects retrievals from multiple embedding models based on standardized similarity; however, it does not outperform vanilla RAG. In contrast, Confident RAG generates responses multiple times using different embedding models and then selects the responses with the highest confidence level, demonstrating average improvements of approximately 10% and 5% over vanilla LLMs and RAG, respectively. The consistent results across different LLMs and embedding models indicate that Confident RAG is an efficient plug-and-play approach for various domains. We will release our code upon publication.

[Arxiv](https://arxiv.org/abs/2507.17442)