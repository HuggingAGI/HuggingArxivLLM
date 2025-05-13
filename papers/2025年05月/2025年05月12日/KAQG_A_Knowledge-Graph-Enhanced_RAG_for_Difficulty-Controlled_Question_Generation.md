# 基于知识图谱增强的RAG框架：难度可控的问题生成方法（KAQG）

发布时间：2025年05月12日

`RAG` `知识图谱`

> KAQG: A Knowledge-Graph-Enhanced RAG for Difficulty-Controlled Question Generation

# 摘要

> KAQG 引入了对检索增强生成（RAG）的决定性突破，明确解决了现有流水线的两大慢性弱点：透明的多步推理路径和细致的认知难度控制。这一创新使 RAG 从被动的检索工具升级为主动可控的试题生成器。技术上，该框架巧妙融合了知识图谱、RAG 检索与教育评估理论，形成了一体化的解决方案。具体而言，领域文档被解析为结构化的知识图谱；基于图感知的检索机制将事实链条传递给大型语言模型；而由布卢姆 taxonomy 等级和项目反应理论（IRT）指导的评估层，则将这些链条转化为心理测量学上可靠的试题。这一跨学科的结合带来了两项重要学术贡献：首先，它揭示了语义图谱如何有效引导 LLM 的推理路径；其次，它实现了难度指标在生成过程中的量化控制，生成的试题其 IRT 参数可与专家基准相媲美。值得注意的是，从知识图谱构建脚本到多智能体推理调度器，再到自动 IRT 验证器，该框架的所有模块均已开源至 GitHub。这一开放设计不仅便于同行实验室复现实验，还支持与基线模型的对比分析以及组件功能的扩展，完全不受许可限制。其可复现的设计理念为严谨的消融研究、跨领域迁移实验以及多步推理基准上的共同排行榜提供了坚实的基础。

> KAQG introduces a decisive breakthrough for Retrieval-Augmented Generation (RAG) by explicitly tackling the two chronic weaknesses of current pipelines: transparent multi-step reasoning and fine-grained cognitive difficulty control. This transforms RAG from a passive retriever into an accountable generator of calibrated exam items. Technically, the framework fuses knowledge graphs, RAG retrieval, and educational assessment theory into a single pipeline. Domain passages are parsed into a structured graph; graph-aware retrieval feeds fact chains to an LLM; and an assessment layer governed by Bloom's Taxonomy levels and Item Response Theory (IRT) transforms those chains into psychometrically sound questions. This cross-disciplinary marriage yields two scholarly contributions: it shows how semantic graph contexts guide LLM reasoning paths, and it operationalizes difficulty metrics within the generation process, producing items whose IRT parameters match expert benchmarks. Every module, from KG construction scripts to the multi-agent reasoning scheduler and the automatic IRT validator, is openly released on GitHub. This enables peer laboratories to replicate experiments, benchmark against baselines, and extend individual components without licensing barriers. Its reproducible design paves the way for rigorous ablation studies, cross-domain transfer experiments, and shared leaderboards on multi-step reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2505.07618)