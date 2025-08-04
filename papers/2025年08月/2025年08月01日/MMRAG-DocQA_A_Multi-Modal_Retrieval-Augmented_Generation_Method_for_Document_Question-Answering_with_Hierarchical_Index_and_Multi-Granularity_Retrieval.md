# MMRAG-DocQA：一种采用层次索引与多粒度检索的多模态增强生成方法，用于文档问答

发布时间：2025年08月01日

`RAG` `文档处理` `问答系统`

> MMRAG-DocQA: A Multi-Modal Retrieval-Augmented Generation Method for Document Question-Answering with Hierarchical Index and Multi-Granularity Retrieval

# 摘要

> 多模态长上下文文档问答任务旨在从多页分布的多模态证据（如文本、表格、图表、图像和布局）中定位并整合信息，以实现精准的问题理解和答案生成。现有方法主要分为基于大型视觉-语言模型（LVLM）和基于检索增强生成（RAG）两类。然而，前者容易产生幻觉，而后者则在跨模态连接和跨页整合方面存在不足。针对这些问题，我们提出了一种新型多模态RAG模型——MMRAG-DocQA，该模型通过整合长跨度页面的文本和视觉信息，显著提升了问答的准确性。我们设计了一种层次索引方法，通过整合页面内的块和跨页的块，实现了多模态关联和跨页长距离依赖的联合构建。借助联合相似度评估和基于大语言模型的重新排序，我们提出了一种多粒度语义检索方法，涵盖页面级父页面检索和文档级摘要检索，从而有效促进多模态证据的连接、长距离证据的整合与推理。实验结果在MMLongBench-Doc和LongDocURL两个公开数据集上验证了MMRAG-DocQA方法在处理多模态、多页文档时的显著优势。

> The multi-modal long-context document question-answering task aims to locate and integrate multi-modal evidences (such as texts, tables, charts, images, and layouts) distributed across multiple pages, for question understanding and answer generation. The existing methods can be categorized into Large Vision-Language Model (LVLM)-based and Retrieval-Augmented Generation (RAG)-based methods. However, the former were susceptible to hallucinations, while the latter struggled for inter-modal disconnection and cross-page fragmentation. To address these challenges, a novel multi-modal RAG model, named MMRAG-DocQA, was proposed, leveraging both textual and visual information across long-range pages to facilitate accurate question answering. A hierarchical indexing method with the integration of flattened in-page chunks and topological cross-page chunks was designed to jointly establish in-page multi-modal associations and long-distance cross-page dependencies. By means of joint similarity evaluation and large language model (LLM)-based re-ranking, a multi-granularity semantic retrieval method, including the page-level parent page retrieval and document-level summary retrieval, was proposed to foster multi-modal evidence connection and long-distance evidence integration and reasoning. Experimental results performed on public datasets, MMLongBench-Doc and LongDocURL, demonstrated the superiority of our MMRAG-DocQA method in understanding and answering modality-rich and multi-page documents.

[Arxiv](https://arxiv.org/abs/2508.00579)