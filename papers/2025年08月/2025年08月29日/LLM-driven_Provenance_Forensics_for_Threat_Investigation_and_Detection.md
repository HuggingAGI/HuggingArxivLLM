# LLM驱动的面向威胁调查与检测的溯源取证

发布时间：2025年08月29日

`Agent` `基础理论`

> LLM-driven Provenance Forensics for Threat Investigation and Detection

# 摘要

> 我们推出了PROVSEEK——一个基于LLM的智能体框架，专为自动化溯源驱动取证分析与威胁情报提取而设计。该框架借助专用工具链生成精确的上下文感知查询，动态融合向量化威胁报告知识库与系统溯源数据库数据，从而高效检索相关上下文。PROVSEEK能够解析溯源查询，协调多个特定角色智能体以减少幻觉，并生成结构化、可验证事实的取证摘要。通过整合智能体编排、检索增强生成（RAG）与思维链（CoT）推理，PROVSEEK实现了自适应多步分析：迭代优化假设、验证支持证据，最终生成可扩展且可解释的攻击行为取证解释。将溯源数据与智能体推理相结合，PROVSEEK开创了基于事实的智能体取证新范式，可用于调查高级持续性威胁（APTs）。我们在公开DARPA数据集上的综合评估显示：在情报提取任务中，PROVSEEK性能超越基于检索的方法，上下文精确率/召回率提升34%；在威胁检测任务中，相比基线智能体AI方法和最先进的（SOTA）基于溯源的入侵检测系统（PIDS），其精确率/召回率分别提高22%和29%。

> We introduce PROVSEEK, an LLM-powered agentic framework for automated provenance-driven forensic analysis and threat intelligence extraction. PROVSEEK employs specialized toolchains to dynamically retrieve relevant context by generating precise, context-aware queries that fuse a vectorized threat report knowledge base with data from system provenance databases. The framework resolves provenance queries, orchestrates multiple role-specific agents to mitigate hallucinations, and synthesizes structured, ground-truth verifiable forensic summaries. By combining agent orchestration with Retrieval-Augmented Generation (RAG) and chain-of-thought (CoT) reasoning, PROVSEEK enables adaptive multi-step analysis that iteratively refines hypotheses, verifies supporting evidence, and produces scalable, interpretable forensic explanations of attack behaviors. By combining provenance data with agentic reasoning, PROVSEEK establishes a new paradigm for grounded agentic forecics to investigate APTs. We conduct a comprehensive evaluation on publicly available DARPA datasets, demonstrating that PROVSEEK outperforms retrieval-based methods for intelligence extraction task, achieving a 34% improvement in contextual precision/recall; and for threat detection task, PROVSEEK achieves 22%/29% higher precision/recall compared to both a baseline agentic AI approach and State-Of-The-Art (SOTA) Provenance-based Intrusion Detection System (PIDS).

[Arxiv](https://arxiv.org/abs/2508.21323)