# <翻译失败>

发布时间：2025年08月30日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> GOSU: Retrieval-Augmented Generation with Global-Level Optimized Semantic Unit-Centric Framework

# 摘要

> <翻译失败>

> Building upon the standard graph-based Retrieval-Augmented Generation (RAG), the introduction of heterogeneous graphs and hypergraphs aims to enrich retrieval and generation by leveraging the relationships between multiple entities through the concept of semantic units (SUs). But this also raises a key issue: The extraction of high-level SUs limited to local text chunks is prone to ambiguity, complex coupling, and increased retrieval overhead due to the lack of global knowledge or the neglect of fine-grained relationships. To address these issues, we propose GOSU, a semantic unit-centric RAG framework that efficiently performs global disambiguation and utilizes SUs to capture interconnections between different nodes across the global context. In the graph construction phase, GOSU performs global merging on the pre-extracted SUs from local text chunks and guides entity and relationship extraction, reducing the difficulty of coreference resolution while uncovering global semantic objects across text chunks. In the retrieval and generation phase, we introduce hierarchical keyword extraction and semantic unit completion. The former uncovers the fine-grained binary relationships overlooked by the latter, while the latter compensates for the coarse-grained n-ary relationships missing from the former. Evaluation across multiple tasks demonstrates that GOSU outperforms the baseline RAG methods in terms of generation quality.

[Arxiv](https://arxiv.org/abs/2509.00449)