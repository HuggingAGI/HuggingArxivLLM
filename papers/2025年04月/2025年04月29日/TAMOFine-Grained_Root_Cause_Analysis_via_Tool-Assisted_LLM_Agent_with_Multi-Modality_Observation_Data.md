# TAMO：基于工具辅助的LLM智能体与多模态观测数据的细粒度根本原因分析

发布时间：2025年04月29日

`LLM应用` `智能运维`

> TAMO:Fine-Grained Root Cause Analysis via Tool-Assisted LLM Agent with Multi-Modality Observation Data

# 摘要

> 随着分布式系统的发展，微服务和云原生技术已成为现代企业软件开发的核心。然而，这些技术在带来优势的同时，也增加了系统复杂性和运维挑战。传统的问题根源分析（RCA）难以实现自动化故障响应，严重依赖人工干预。近年来，大型语言模型（LLMs）在上下文推理和领域知识整合方面取得了突破，为智能运维（AIOps）提供了新的解决方案。然而，现有的基于LLM的方法面临三个关键挑战：文本输入限制、动态服务依赖的幻觉以及上下文窗口限制。为了解决这些问题，我们提出了一种工具辅助的多模态观测数据LLM代理，即TAMO，用于细粒度的RCA。它将多模态观测数据统一为时间对齐的表示，以提取一致的特征，并利用专门的根因定位和故障分类工具来感知环境。这种方法克服了LLM在处理实时变化的服务依赖和原始观测数据方面的局限性，并通过将关键信息结构化为提示，引导LLM生成与系统上下文一致的修复策略。实验结果表明，TAMO在处理以异质性和常见故障类型为特征的公共数据集时，在根本原因分析方面表现出色，证明了其有效性。

> With the development of distributed systems, microservices and cloud native technologies have become central to modern enterprise software development. Despite bringing significant advantages, these technologies also increase system complexity and operational challenges. Traditional root cause analysis (RCA) struggles to achieve automated fault response, heavily relying on manual intervention. In recent years, large language models (LLMs) have made breakthroughs in contextual inference and domain knowledge integration, providing new solutions for Artificial Intelligence for Operations (AIOps). However, Existing LLM-based approaches face three key challenges: text input constraints, dynamic service dependency hallucinations, and context window limitations. To address these issues, we propose a tool-assisted LLM agent with multi-modality observation data, namely TAMO, for fine-grained RCA. It unifies multi-modal observational data into time-aligned representations to extract consistent features and employs specialized root cause localization and fault classification tools for perceiving the contextual environment. This approach overcomes the limitations of LLM in handling real-time changing service dependencies and raw observational data and guides LLM to generate repair strategies aligned with system contexts by structuring key information into a prompt. Experimental results show that TAMO performs well in root cause analysis when dealing with public datasets characterized by heterogeneity and common fault types, demonstrating its effectiveness.

[Arxiv](https://arxiv.org/abs/2504.20462)