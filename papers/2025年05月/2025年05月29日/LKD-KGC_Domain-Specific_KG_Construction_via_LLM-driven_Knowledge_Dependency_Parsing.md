# LKD-KGC: 通过 LLM 驱动的知识依赖解析实现领域特定知识图谱构建

发布时间：2025年05月29日

`LLM应用` `知识图谱`

> LKD-KGC: Domain-Specific KG Construction via LLM-driven Knowledge Dependency Parsing

# 摘要

> 知识图谱（KGs）将现实世界中的实体及其关系结构化为三元组，显著提升了机器推理能力。然而，领域特定知识图谱的构建虽有益处，但手动构建效率低且需专业知识。近期基于大型语言模型（LLMs）的KGC方法，如模式引导和参考知识整合，虽有效，但受限于人工定义模式、单文档处理和公开领域参考。针对这些限制，我们提出LKD-KGC框架，通过自主分析文档仓库推断知识依赖，利用LLM驱动排序确定最优处理顺序，并结合跨文档上下文自动生成实体模式。此模式指导无监督提取，无需依赖预定义结构或外部知识。实验表明，LKD-KGC在精确率和召回率上比现有方法提升10%至20%，展现了其在构建高质量领域特定KG的潜力。

> Knowledge Graphs (KGs) structure real-world entities and their relationships into triples, enhancing machine reasoning for various tasks. While domain-specific KGs offer substantial benefits, their manual construction is often inefficient and requires specialized knowledge. Recent approaches for knowledge graph construction (KGC) based on large language models (LLMs), such as schema-guided KGC and reference knowledge integration, have proven efficient. However, these methods are constrained by their reliance on manually defined schema, single-document processing, and public-domain references, making them less effective for domain-specific corpora that exhibit complex knowledge dependencies and specificity, as well as limited reference knowledge. To address these challenges, we propose LKD-KGC, a novel framework for unsupervised domain-specific KG construction. LKD-KGC autonomously analyzes document repositories to infer knowledge dependencies, determines optimal processing sequences via LLM driven prioritization, and autoregressively generates entity schema by integrating hierarchical inter-document contexts. This schema guides the unsupervised extraction of entities and relationships, eliminating reliance on predefined structures or external knowledge. Extensive experiments show that compared with state-of-the-art baselines, LKD-KGC generally achieves improvements of 10% to 20% in both precision and recall rate, demonstrating its potential in constructing high-quality domain-specific KGs.

[Arxiv](https://arxiv.org/abs/2505.24163)