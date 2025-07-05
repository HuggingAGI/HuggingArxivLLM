# CROP: 通过参数引导实现LLM驱动的电路检索与优化

发布时间：2025年07月02日

`LLM应用` `集成电路` `半导体制造`

> CROP: Circuit Retrieval and Optimization with Parameter Guidance using LLMs

# 摘要

> 现代超大规模集成电路 (VLSI) 设计离不开电子设计自动化 (EDA) 工具的支持。然而，由于 EDA 算法的复杂性，庞大的参数空间给芯片优化带来了巨大挑战——即使参数数量适中，也会产生一个难以探索的巨大解空间。尽管如此，耗时费力且受限于专家经验的手动参数选择仍是行业主流。为解决这一难题，我们推出了 CROP——首个基于大型语言模型 (LLM) 的自动 VLSI 设计流程调优框架。CROP 包括三大创新模块：(1) 一种可扩展的 RTL 源代码到密集向量表示的转换方法，(2) 基于嵌入的语义相似电路匹配系统，以及 (3) 通过相似设计先验知识约束搜索过程的增强型 LLM 引导参数搜索系统。实验结果表明，CROP 在工业设计中以更少的迭代次数实现了更优的质量结果，其中包括 9.9% 的功耗降低，展现出显著优势。

> Modern very large-scale integration (VLSI) design requires the implementation of integrated circuits using electronic design automation (EDA) tools. Due to the complexity of EDA algorithms, the vast parameter space poses a huge challenge to chip design optimization, as the combination of even moderate numbers of parameters creates an enormous solution space to explore. Manual parameter selection remains industrial practice despite being excessively laborious and limited by expert experience. To address this issue, we present CROP, the first large language model (LLM)-powered automatic VLSI design flow tuning framework. Our approach includes: (1) a scalable methodology for transforming RTL source code into dense vector representations, (2) an embedding-based retrieval system for matching designs with semantically similar circuits, and (3) a retrieval-augmented generation (RAG)-enhanced LLM-guided parameter search system that constrains the search process with prior knowledge from similar designs. Experiment results demonstrate CROP's ability to achieve superior quality-of-results (QoR) with fewer iterations than existing approaches on industrial designs, including a 9.9% reduction in power consumption.

[Arxiv](https://arxiv.org/abs/2507.02128)