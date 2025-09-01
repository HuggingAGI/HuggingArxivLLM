# MIRAGE：基于并行图检索增强推理链的测试时推理扩展

发布时间：2025年08月25日

`RAG` `医疗健康`

> MIRAGE: Scaling Test-Time Inference with Parallel Graph-Retrieval-Augmented Reasoning Chains

# 摘要

> 大型推理模型（LRMs）借助思维链提示，在测试时扩展能力上已取得显著进步。目前如search-o1等方法虽将检索增强生成（RAG）融入多步推理过程，但依赖单一的线性推理链，且以扁平、脱离上下文的方式整合非结构化文本信息。因此，这些方法会导致推理链中的错误不断累积，严重限制了其在医学问答（QA）任务中的效果——这类任务对准确性和可追溯性均有极高要求。为解决这些问题，我们提出了MIRAGE（多链推理与检索增强图探索）——一种基于结构化医学知识图谱进行动态多链推理的新型测试时可扩展框架。具体而言，MIRAGE的核心机制包括：1）将复杂查询拆解为实体锚定的子问题；2）执行并行推理链；3）通过邻居扩展与多跳遍历自适应检索证据；4）利用跨链验证整合答案，解决矛盾冲突。在三个医学QA基准数据集（GenMedGPT-5k、CMCQA和ExplainCPE）上的实验显示，MIRAGE在自动评估和人工评估中均表现稳定，持续优于GPT-4o、思维树变体及其他检索增强基线模型。此外，MIRAGE通过生成明确的推理链提升了可解释性——每条推理链都能将事实主张追溯到知识图谱中的具体路径，使其非常适用于复杂的医学推理场景。相关代码将公开以供后续研究。

> Large reasoning models (LRMs) have shown significant progress in test-time scaling through chain-of-thought prompting. Current approaches like search-o1 integrate retrieval augmented generation (RAG) into multi-step reasoning processes but rely on a single, linear reasoning chain while incorporating unstructured textual information in a flat, context-agnostic manner. As a result, these approaches can lead to error accumulation throughout the reasoning chain, which significantly limits its effectiveness in medical question-answering (QA) tasks where both accuracy and traceability are critical requirements. To address these challenges, we propose MIRAGE (Multi-chain Inference with Retrieval-Augmented Graph Exploration), a novel test-time scalable reasoning framework that performs dynamic multi-chain inference over structured medical knowledge graphs. Specifically, MIRAGE 1) decomposes complex queries into entity-grounded sub-questions, 2) executes parallel inference chains, 3) retrieves evidence adaptively via neighbor expansion and multi-hop traversal, and 4) integrates answers using cross-chain verification to resolve contradictions. Experiments on three medical QA benchmarks (GenMedGPT-5k, CMCQA, and ExplainCPE) show that MIRAGE consistently outperforms GPT-4o, Tree-of-Thought variants, and other retrieval-augmented baselines in both automatic and human evaluations. Additionally, MIRAGE improves interpretability by generating explicit reasoning chains that trace each factual claim to concrete chains within the knowledge graph, making it well-suited for complex medical reasoning scenarios. The code will be available for further research.

[Arxiv](https://arxiv.org/abs/2508.18260)