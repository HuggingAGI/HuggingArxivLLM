# 基于记忆增强的查询重构方法，提升LLM的知识图推理能力

发布时间：2025年03月07日

`LLM应用

理由：这篇论文探讨了大型语言模型在知识图谱问答任务中的应用，并提出了一种改进方法，属于LLM的应用层面研究。` `知识图谱` `问答系统`

> Memory-augmented Query Reconstruction for LLM-based Knowledge Graph Reasoning

# 摘要

> 大型语言模型（LLMs）在知识图谱问答（KGQA）任务中表现出色，但现有方法常混淆工具使用与知识推理，导致输出难读并产生幻觉式工具调用，阻碍了KGQA的发展。为解决这一问题，我们提出MemQ方法，通过LLM构建的查询记忆将模型与工具调用解耦。MemQ利用自然语言推理和增强型查询重构来优化KGQA过程，并设计了一种高效易懂的推理方式，显著提升了LLM在KGQA中的推理能力。实验结果显示，MemQ在WebQSP和CWQ基准测试中达到了当前最优性能。

> Large language models (LLMs) have achieved remarkable performance on knowledge graph question answering (KGQA) tasks by planning and interacting with knowledge graphs. However, existing methods often confuse tool utilization with knowledge reasoning, harming readability of model outputs and giving rise to hallucinatory tool invocations, which hinder the advancement of KGQA. To address this issue, we propose Memory-augmented Query Reconstruction for LLM-based Knowledge Graph Reasoning (MemQ) to decouple LLM from tool invocation tasks using LLM-built query memory. By establishing a memory module with explicit descriptions of query statements, the proposed MemQ facilitates the KGQA process with natural language reasoning and memory-augmented query reconstruction. Meanwhile, we design an effective and readable reasoning to enhance the LLM's reasoning capability in KGQA. Experimental results that MemQ achieves state-of-the-art performance on widely used benchmarks WebQSP and CWQ.

[Arxiv](https://arxiv.org/abs/2503.05193)