# SCORE：提升AI叙事能力，通过故事连贯性与检索增强

发布时间：2025年03月30日

`LLM应用` `叙事生成` `内容生成`

> SCORE: Story Coherence and Retrieval Enhancement for AI Narratives

# 摘要

> 大型语言模型（LLMs）擅长生成创意叙述，但在复杂故事中常面临长期连贯性和情感一致性不足的问题。为解决这一挑战，我们提出了SCORE框架，整合了动态状态跟踪、上下文感知摘要和混合检索三大核心组件。通过时间对齐的增强检索生成流水线，系统能够有效验证上下文一致性。实验结果显示，相比基线GPT模型，SCORE在连贯性、情感一致性和幻觉控制方面均有显著提升。其模块化设计不仅支持知识图谱的持续构建，还实现了对多种LLM后端的兼容，为需要长期一致性的工业级叙事系统提供了高效且可解释的解决方案。

> Large Language Models (LLMs) excel at generating creative narratives but struggle with long-term coherence and emotional consistency in complex stories. To address this, we propose SCORE (Story Coherence and Retrieval Enhancement), a framework integrating three components: 1) Dynamic State Tracking (monitoring objects/characters via symbolic logic), 2) Context-Aware Summarization (hierarchical episode summaries for temporal progression), and 3) Hybrid Retrieval (combining TF-IDF keyword relevance with cosine similarity-based semantic embeddings). The system employs a temporally-aligned Retrieval-Augmented Generation (RAG) pipeline to validate contextual consistency. Evaluations show SCORE achieves 23.6% higher coherence (NCI-2.0 benchmark), 89.7% emotional consistency (EASM metric), and 41.8% fewer hallucinations versus baseline GPT models. Its modular design supports incremental knowledge graph construction for persistent story memory and multi-LLM backend compatibility, offering an explainable solution for industrial-scale narrative systems requiring long-term consistency.

[Arxiv](https://arxiv.org/abs/2503.23512)