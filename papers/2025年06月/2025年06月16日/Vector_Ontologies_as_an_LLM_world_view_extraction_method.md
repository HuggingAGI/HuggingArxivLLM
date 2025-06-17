# 向量本体：LLM 世界观的提取方法

发布时间：2025年06月16日

`LLM应用` `人工智能` `数据分析`

> Vector Ontologies as an LLM world view extraction method

# 摘要

> <翻译失败>

> Large Language Models (LLMs) possess intricate internal representations of the world, yet these latent structures are notoriously difficult to interpret or repurpose beyond the original prediction task. Building on our earlier work (Rothenfusser, 2025), which introduced the concept of vector ontologies as a framework for translating high-dimensional neural representations into interpretable geometric structures, this paper provides the first empirical validation of that approach. A vector ontology defines a domain-specific vector space spanned by ontologically meaningful dimensions, allowing geometric analysis of concepts and relationships within a domain. We construct an 8-dimensional vector ontology of musical genres based on Spotify audio features and test whether an LLM's internal world model of music can be consistently and accurately projected into this space. Using GPT-4o-mini, we extract genre representations through multiple natural language prompts and analyze the consistency of these projections across linguistic variations and their alignment with ground-truth data. Our results show (1) high spatial consistency of genre projections across 47 query formulations, (2) strong alignment between LLM-inferred genre locations and real-world audio feature distributions, and (3) evidence of a direct relationship between prompt phrasing and spatial shifts in the LLM's inferred vector ontology. These findings demonstrate that LLMs internalize structured, repurposable knowledge and that vector ontologies offer a promising method for extracting and analyzing this knowledge in a transparent and verifiable way.

[Arxiv](https://arxiv.org/abs/2506.13252)