# MMMR：大规模多模态推理任务的基准测试

发布时间：2025年05月22日

`LLM应用` `多模态`

> MMMR: Benchmarking Massive Multi-Modal Reasoning Tasks

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展实现了语言、视觉和结构化输入的统一处理，为逻辑推理、空间思维和科学分析等复杂任务开辟了新可能。然而，尽管MLLMs-T（配备中间思考轨迹的模型）展现出潜力，但其推理能力仍存在诸多未解之谜，且缺乏统一的评估标准。现有研究多聚焦于感知能力或答案正确性，对模型推理机制和失败原因的洞察有限。为解决这一问题，我们推出了MMM-R，一个全新的基准测试，专注于评估具有明确思考过程的多模态推理能力。MMM-R包含两大部分：1）一个包含1,083个问题的高难度数据集，涵盖六种多样化推理类型，涉及符号深度和多跳推理需求；2）一个模块化的推理轨迹评估管道（RTEP），通过相关性、一致性和结构化错误标注等多维度指标，全面评估推理质量。实验结果表明，MLLMs-T整体表现优于传统模型，但即使是Claude-3.7-Sonnet和Gemini-2.5 Pro等顶尖模型，仍存在推理缺陷，如不一致性和过度思考。这一基准测试不仅揭示了准确率与推理质量之间的差距，更为未来多模态推理系统的开发提供了一个实用的评估框架。总体而言，MMM-R为评估、比较和优化下一代多模态推理系统奠定了坚实基础。

> Recent advances in Multi-Modal Large Language Models (MLLMs) have enabled unified processing of language, vision, and structured inputs, opening the door to complex tasks such as logical deduction, spatial reasoning, and scientific analysis. Despite their promise, the reasoning capabilities of MLLMs, particularly those augmented with intermediate thinking traces (MLLMs-T), remain poorly understood and lack standardized evaluation benchmarks. Existing work focuses primarily on perception or final answer correctness, offering limited insight into how models reason or fail across modalities. To address this gap, we introduce the MMMR, a new benchmark designed to rigorously evaluate multi-modal reasoning with explicit thinking. The MMMR comprises 1) a high-difficulty dataset of 1,083 questions spanning six diverse reasoning types with symbolic depth and multi-hop demands and 2) a modular Reasoning Trace Evaluation Pipeline (RTEP) for assessing reasoning quality beyond accuracy through metrics like relevance, consistency, and structured error annotations. Empirical results show that MLLMs-T overall outperform non-thinking counterparts, but even top models like Claude-3.7-Sonnet and Gemini-2.5 Pro suffer from reasoning pathologies such as inconsistency and overthinking. This benchmark reveals persistent gaps between accuracy and reasoning quality and provides an actionable evaluation pipeline for future model development. Overall, the MMMR offers a scalable foundation for evaluating, comparing, and improving the next generation of multi-modal reasoning systems.

[Arxiv](https://arxiv.org/abs/2505.16459)