# 多模态分子嵌入的表示与集成平台

发布时间：2025年07月09日

`其他` `生物医学` `生物信息学`

> Platform for Representation and Integration of multimodal Molecular Embeddings

# 摘要

> 现有的分子嵌入方法多局限于特定任务或数据模态，难以全面捕捉基因功能及其在不同生物环境中的相互作用。本研究系统评估了生物分子的知识表示，覆盖组学实验数据、文献文本数据和知识图谱表示三大主要数据源，采用任务无关的方式进行跨维度分析。为了区分有意义的生物信号与偶然相关性，我们开发了一种调整后的单值向量典型相关分析（SVCCA）方法，用于量化不同数据模态和来源之间的信号冗余与互补性。分析结果表明，现有嵌入方法捕获的分子信号多不重叠，凸显了整合嵌入方法的重要性。基于此，我们提出了多模态分子嵌入表示与整合平台（PRISME），该平台利用自动编码器整合异质嵌入，构建统一的多模态表示。在多种基准任务中，PRISME展现了稳定的表现，并在缺失值插补方面超越了单一嵌入方法。这一新框架为生物分子的全面建模提供了支持，推动了多模态嵌入方法的发展，优化了其在生物医学机器学习中的应用。

> Existing machine learning methods for molecular (e.g., gene) embeddings are restricted to specific tasks or data modalities, limiting their effectiveness within narrow domains. As a result, they fail to capture the full breadth of gene functions and interactions across diverse biological contexts. In this study, we have systematically evaluated knowledge representations of biomolecules across multiple dimensions representing a task-agnostic manner spanning three major data sources, including omics experimental data, literature-derived text data, and knowledge graph-based representations. To distinguish between meaningful biological signals from chance correlations, we devised an adjusted variant of Singular Vector Canonical Correlation Analysis (SVCCA) that quantifies signal redundancy and complementarity across different data modalities and sources. These analyses reveal that existing embeddings capture largely non-overlapping molecular signals, highlighting the value of embedding integration. Building on this insight, we propose Platform for Representation and Integration of multimodal Molecular Embeddings (PRISME), a machine learning based workflow using an autoencoder to integrate these heterogeneous embeddings into a unified multimodal representation. We validated this approach across various benchmark tasks, where PRISME demonstrated consistent performance, and outperformed individual embedding methods in missing value imputations. This new framework supports comprehensive modeling of biomolecules, advancing the development of robust, broadly applicable multimodal embeddings optimized for downstream biomedical machine learning applications.

[Arxiv](https://arxiv.org/abs/2507.07367)