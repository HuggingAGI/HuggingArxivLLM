# OMGM：整合多粒度与多模态，实现高效的多模态检索

发布时间：2025年05月10日

`RAG` `视觉问答` `视觉语言处理`

> OMGM: Orchestrate Multiple Granularities and Modalities for Efficient Multimodal Retrieval

# 摘要

> 视觉语言检索增强生成（RAG）已成为解决基于知识的视觉问答（KB-VQA）的有效方案，该任务需要超越图像中呈现的视觉内容，借助外部知识进行解答。视觉语言RAG系统的有效性取决于多模态检索能力，这一过程本身因查询和知识库中模态与知识粒度的多样性而具有挑战性。现有方法尚未充分挖掘这些元素间的潜在交互作用。我们提出了一种多模态RAG系统，采用粗细结合、多阶段检索策略，协调多种粒度与模态以提升效果。我们的系统首先进行广泛初始搜索，以对齐跨模态检索的知识粒度，随后通过多模态融合重新排序，捕捉细微的多模态信息以选择顶级实体。接着，文本重新排序器筛选出最相关的细粒度部分用于增强生成。在InfoSeek和Encyclopedic-VQA基准上的大量实验表明，我们的方法实现了最先进的检索性能和极具竞争力的问答结果，凸显了其在推动KB-VQA系统发展中的有效性。

> Vision-language retrieval-augmented generation (RAG) has become an effective approach for tackling Knowledge-Based Visual Question Answering (KB-VQA), which requires external knowledge beyond the visual content presented in images. The effectiveness of Vision-language RAG systems hinges on multimodal retrieval, which is inherently challenging due to the diverse modalities and knowledge granularities in both queries and knowledge bases. Existing methods have not fully tapped into the potential interplay between these elements. We propose a multimodal RAG system featuring a coarse-to-fine, multi-step retrieval that harmonizes multiple granularities and modalities to enhance efficacy. Our system begins with a broad initial search aligning knowledge granularity for cross-modal retrieval, followed by a multimodal fusion reranking to capture the nuanced multimodal information for top entity selection. A text reranker then filters out the most relevant fine-grained section for augmented generation. Extensive experiments on the InfoSeek and Encyclopedic-VQA benchmarks show our method achieves state-of-the-art retrieval performance and highly competitive answering results, underscoring its effectiveness in advancing KB-VQA systems.

[Arxiv](https://arxiv.org/abs/2505.07879)