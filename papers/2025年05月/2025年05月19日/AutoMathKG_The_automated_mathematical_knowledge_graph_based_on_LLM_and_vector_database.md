# AutoMathKG：基于大型语言模型（LLM）和向量数据库构建的自动化数学知识图谱

发布时间：2025年05月19日

`其他` `知识图谱`

> AutoMathKG: The automated mathematical knowledge graph based on LLM and vector database

# 摘要

> 数学知识图谱（KG）以结构化方式呈现数学知识。使用自然语言构建数学KG是一项至关重要但充满挑战的任务。现有研究存在两大局限：一是受限于语料库完整性，常需手动补充或舍弃不完整知识；二是难以完全自动化整合多样化知识来源。本文提出AutoMathKG——一种高质量、广覆盖、多维度且支持自动更新的数学KG。AutoMathKG将数学视为由定义、定理和问题构成的庞大有向图，引用关系作为边连接各实体。它整合了ProofWiki、教科书、arXiv论文和TheoremQA的知识，并通过大规模语言模型（LLMs）的在上下文学习进行数据增强。为实现相似实体搜索，通过两种嵌入策略利用SBERT构建了向量数据库MathVD。为实现自动更新，本文提出了两种机制：知识完善机制通过Math LLM与AutoMathKG交互，提供缺失的证明或解答；知识融合机制利用MathVD检索相似实体，并通过LLM判断是否合并或新增实体。实验结果表明，AutoMathKG系统具备先进性能和广泛应用性，包括在MathVD中优于五种基线的可达性查询结果，以及Math LLM中强大的数学推理能力。

> A mathematical knowledge graph (KG) presents knowledge within the field of mathematics in a structured manner. Constructing a math KG using natural language is an essential but challenging task. There are two major limitations of existing works: first, they are constrained by corpus completeness, often discarding or manually supplementing incomplete knowledge; second, they typically fail to fully automate the integration of diverse knowledge sources. This paper proposes AutoMathKG, a high-quality, wide-coverage, and multi-dimensional math KG capable of automatic updates. AutoMathKG regards mathematics as a vast directed graph composed of Definition, Theorem, and Problem entities, with their reference relationships as edges. It integrates knowledge from ProofWiki, textbooks, arXiv papers, and TheoremQA, enhancing entities and relationships with large language models (LLMs) via in-context learning for data augmentation. To search for similar entities, MathVD, a vector database, is built through two designed embedding strategies using SBERT. To automatically update, two mechanisms are proposed. For knowledge completion mechanism, Math LLM is developed to interact with AutoMathKG, providing missing proofs or solutions. For knowledge fusion mechanism, MathVD is used to retrieve similar entities, and LLM is used to determine whether to merge with a candidate or add as a new entity. A wide range of experiments demonstrate the advanced performance and broad applicability of the AutoMathKG system, including superior reachability query results in MathVD compared to five baselines and robust mathematical reasoning capability in Math LLM.

[Arxiv](https://arxiv.org/abs/2505.13406)