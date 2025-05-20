# 加速自适应检索增强生成，通过指令驱动的检索重叠表示降维

发布时间：2025年05月19日

`RAG` `信息检索`

> Accelerating Adaptive Retrieval Augmented Generation via Instruction-Driven Representation Reduction of Retrieval Overlaps

# 摘要

> 检索增强生成（RAG）是扩展大型语言模型知识的重要方法。为提升复杂查询的处理效果，研究者开发了自适应-RAG（A-RAG），通过多次与外部知识库交互来优化生成质量。然而，尽管A-RAG有效，其效率问题依然突出，这主要源于其依赖多次生成迭代的特性。现有A-RAG方法从头处理所有检索内容，却忽视了不同轮次检索结果间可能存在显著内容重叠的情况。这种重叠内容的冗余表示导致了大量重复计算，从而影响整体效率。为解决此问题，本文提出了一种无模型依赖的方法，可广泛应用于各类A-RAG方法，专为减少由检索结果重叠引发的冗余表示过程。具体而言，我们采用缓存访问和并行生成来分别加速预填充和解码阶段。此外，我们还提出了一种基于指令的模块，进一步引导模型以更适合大语言模型的方式，更有效地关注内容的各个部分。实验结果表明，与现有方法相比，我们的方法在保持相同生成质量的同时，预填充和解码阶段的平均加速倍数分别达到2.79和2.33倍。

> Retrieval-augmented generation (RAG) has emerged as a pivotal method for expanding the knowledge of large language models. To handle complex queries more effectively, researchers developed Adaptive-RAG (A-RAG) to enhance the generated quality through multiple interactions with external knowledge bases. Despite its effectiveness, A-RAG exacerbates the pre-existing efficiency challenges inherent in RAG, which are attributable to its reliance on multiple iterations of generation. Existing A-RAG approaches process all retrieved contents from scratch. However, they ignore the situation where there is a significant overlap in the content of the retrieval results across rounds. The overlapping content is redundantly represented, which leads to a large proportion of repeated computations, thus affecting the overall efficiency. To address this issue, this paper introduces a model-agnostic approach that can be generally applied to A-RAG methods, which is dedicated to reducing the redundant representation process caused by the overlapping of retrieval results. Specifically, we use cache access and parallel generation to speed up the prefilling and decoding stages respectively. Additionally, we also propose an instruction-driven module to further guide the model to more effectively attend to each part of the content in a more suitable way for LLMs. Experiments show that our approach achieves 2.79 and 2.33 times significant acceleration on average for prefilling and decoding respectively while maintaining equal generation quality.

[Arxiv](https://arxiv.org/abs/2505.12731)