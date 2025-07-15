# 使用层次化文本分段切块提升检索增强生成效果

发布时间：2025年07月14日

`RAG` `问答系统` `知识图谱`

> Enhancing Retrieval Augmented Generation with Hierarchical Text Segmentation Chunking

# 摘要

> RAG系统通常借助分块策略实现检索，这些策略通过赋予大型语言模型（LLMs）访问外部知识的能力，确保了检索信息的时效性和领域相关性。然而，传统方法往往难以生成包含足够语义信息的分块，因为它们未能考虑到潜在的文本结构。本文提出了一种新型框架，通过整合层次化文本分割与聚类技术，生成更具意义且语义连贯的分块，从而提升RAG系统性能。在推理过程中，该框架利用分段级和聚类级的向量表示进行信息检索，从而提高了获取更精确且上下文相关的信息的可能性。在NarrativeQA、QuALITY和QASPER数据集上的评估表明，与传统分块技术相比，本方法取得了显著提升。

> Retrieval-Augmented Generation (RAG) systems commonly use chunking strategies for retrieval, which enhance large language models (LLMs) by enabling them to access external knowledge, ensuring that the retrieved information is up-to-date and domain-specific. However, traditional methods often fail to create chunks that capture sufficient semantic meaning, as they do not account for the underlying textual structure. This paper proposes a novel framework that enhances RAG by integrating hierarchical text segmentation and clustering to generate more meaningful and semantically coherent chunks. During inference, the framework retrieves information by leveraging both segment-level and cluster-level vector representations, thereby increasing the likelihood of retrieving more precise and contextually relevant information. Evaluations on the NarrativeQA, QuALITY, and QASPER datasets indicate that the proposed method achieved improved results compared to traditional chunking techniques.

[Arxiv](https://arxiv.org/abs/2507.09935)