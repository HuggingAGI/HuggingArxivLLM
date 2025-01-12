# 多模态检索增强生成中的上下文重排序

发布时间：2025年01月08日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在多模态环境下的挑战，特别是如何提升检索阶段的相关性。论文提出了改进的检索方法，以筛选出更相关的上下文，从而提高RAG系统的性能。因此，这篇论文应归类为RAG。` `信息检索` `多模态系统`

> Re-ranking the Context for Multimodal Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）通过引入外部知识，帮助大型语言模型（LLMs）在特定上下文中生成更准确且减少幻觉的响应。然而，多模态RAG系统面临两大挑战：一是检索过程可能选出与用户查询无关的条目（如图像、文档），二是视觉语言模型或多模态语言模型（如GPT-4o）在处理这些条目生成RAG输出时可能产生幻觉。本文聚焦于第一个挑战，旨在提升多模态RAG在检索阶段从知识库中选择相关上下文的能力。我们采用之前工作中设计的相关性评分（RS）度量，用于评估RAG性能，并在检索过程中筛选出更相关的条目。传统的基于嵌入（如CLIP嵌入）和余弦相似度的检索方法在多模态数据上表现欠佳。我们通过引入更高级的相关性度量，能够从知识库中筛选出更相关的片段，并自适应地选择最多$k$个条目，而非固定数量，从而剔除无关内容。基于COCO数据集的实验表明，该方法在提升上下文相关性和生成响应准确性方面效果显著。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) by incorporating external knowledge to generate a response within a context with improved accuracy and reduced hallucinations. However, multi-modal RAG systems face unique challenges: (i) the retrieval process may select irrelevant entries to user query (e.g., images, documents), and (ii) vision-language models or multi-modal language models like GPT-4o may hallucinate when processing these entries to generate RAG output. In this paper, we aim to address the first challenge, i.e, improving the selection of relevant context from the knowledge-base in retrieval phase of the multi-modal RAG. Specifically, we leverage the relevancy score (RS) measure designed in our previous work for evaluating the RAG performance to select more relevant entries in retrieval process. The retrieval based on embeddings, say CLIP-based embedding, and cosine similarity usually perform poorly particularly for multi-modal data. We show that by using a more advanced relevancy measure, one can enhance the retrieval process by selecting more relevant pieces from the knowledge-base and eliminate the irrelevant pieces from the context by adaptively selecting up-to-$k$ entries instead of fixed number of entries. Our evaluation using COCO dataset demonstrates significant enhancement in selecting relevant context and accuracy of the generated response.

[Arxiv](https://arxiv.org/abs/2501.04695)