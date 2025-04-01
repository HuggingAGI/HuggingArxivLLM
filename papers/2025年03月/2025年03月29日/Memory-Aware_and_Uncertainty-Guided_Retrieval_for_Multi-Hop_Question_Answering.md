# # 记忆感知与不确定性引导的多跳问答检索

发布时间：2025年03月29日

`RAG` `问答系统`

> Memory-Aware and Uncertainty-Guided Retrieval for Multi-Hop Question Answering

# 摘要

> 多跳问答需要模型检索并推理多条证据。虽然检索增强生成（RAG）在这一领域取得了进展，但现有方法通常面临两个关键限制：检索步骤固定或过于频繁，以及未能有效利用之前检索到的知识。我们提出MIND框架，通过以下方式解决这些挑战：基于提示的实体提取识别推理相关元素，基于词元级别熵和注意力信号的动态检索触发，以及记忆感知过滤跨推理步骤存储高置信度事实，实现一致的多跳生成。

> Multi-hop question answering (QA) requires models to retrieve and reason over multiple pieces of evidence. While Retrieval-Augmented Generation (RAG) has made progress in this area, existing methods often suffer from two key limitations: (1) fixed or overly frequent retrieval steps, and (2) ineffective use of previously retrieved knowledge.
  We propose MIND (Memory-Informed and INteractive Dynamic RAG), a framework that addresses these challenges through: (i) prompt-based entity extraction to identify reasoning-relevant elements, (ii) dynamic retrieval triggering based on token-level entropy and attention signals, and (iii) memory-aware filtering, which stores high-confidence facts across reasoning steps to enable consistent multi-hop generation.

[Arxiv](https://arxiv.org/abs/2503.23095)