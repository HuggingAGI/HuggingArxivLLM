# RARE：针对检索增强生成系统的检索增强鲁棒性评估

发布时间：2025年05月31日

`RAG` `经济政策`

> RARE: Retrieval-Aware Robustness Evaluation for Retrieval-Augmented Generation Systems

# 摘要

> 检索增强生成（RAG）在提升回答的时效性和事实性方面表现出色。然而，现有的评估方法很少测试这些系统在面对现实世界噪音、内部与外部检索上下文之间的冲突，或快速变化的事实时的表现。我们引入了检索感知鲁棒性评估（RARE），这是一个统一的框架和大规模基准，旨在同时对动态、时效性语料库中的查询和文档扰动进行压力测试。RARE 的一个核心功能是基于知识图谱的合成管道（RARE-Get），它能够从定制语料库中自动提取单跳和多跳关系，并在无需人工干预的情况下生成多层级的问题集。借助这一管道，我们构建了一个包含400份专家级时效性财经、经济与政策文档以及48,322个问题的数据集（RARE-Set），这些问题的分布会随着底层来源的变化而变化。为了量化系统的韧性，我们制定了基于检索条件的鲁棒性指标（RARE-Met），以衡量模型在系统性改变查询、文档或现实世界检索结果时保持正确或恢复的能力。我们的结果显示，RAG 系统对扰动表现出惊人的脆弱性，无论生成器的大小或架构如何，文档鲁棒性始终是最弱的一环。此外，在所有领域中，RAG 系统在多跳查询上的鲁棒性始终低于单跳查询。

> Retrieval-Augmented Generation (RAG) enhances recency and factuality in answers. However, existing evaluations rarely test how well these systems cope with real-world noise, conflicting between internal and external retrieved contexts, or fast-changing facts. We introduce Retrieval-Aware Robustness Evaluation (RARE), a unified framework and large-scale benchmark that jointly stress-tests query and document perturbations over dynamic, time-sensitive corpora. One of the central features of RARE is a knowledge-graph-driven synthesis pipeline (RARE-Get) that automatically extracts single and multi-hop relations from the customized corpus and generates multi-level question sets without manual intervention. Leveraging this pipeline, we construct a dataset (RARE-Set) spanning 400 expert-level time-sensitive finance, economics, and policy documents and 48,322 questions whose distribution evolves as the underlying sources change. To quantify resilience, we formalize retrieval-conditioned robustness metrics (RARE-Met) that capture a model's ability to remain correct or recover when queries, documents, or real-world retrieval results are systematically altered. Our results show that RAG systems exhibit surprising vulnerability to perturbations, with document robustness consistently being the weakest point regardless of generator size or architecture. RAG systems consistently show lower robustness on multi-hop queries than single-hop queries across all domains.

[Arxiv](https://arxiv.org/abs/2506.00789)