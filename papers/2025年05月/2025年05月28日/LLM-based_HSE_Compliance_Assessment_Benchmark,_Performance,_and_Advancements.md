# 基于LLM的HSE合规性评估：基准、性能与进展

发布时间：2025年05月28日

`LLM应用

理由：这篇论文主要探讨了大型语言模型在HSE合规评估中的应用，构建了一个基准数据集，并评估了不同模型的表现，同时提出了一种新的提示方法。研究集中在应用层面，属于LLM应用类别。` `HSE合规评估` `合规评估技术`

> LLM-based HSE Compliance Assessment: Benchmark, Performance, and Advancements

# 摘要

> 健康、安全与环境 (HSE) 合规评估需要在复杂法规和人-机-环境交互中进行动态实时决策。大型语言模型 (LLMs) 在决策智能和情境对话方面潜力巨大，但在 HSE 领域的专业知识和结构化法律推理能力尚待深入探索。我们推出 HSE-Bench，这是首个专为评估 LLM 的 HSE 合规评估能力设计的基准数据集。该数据集包含 1,000 多个精选问题，涵盖法规、法院案例、安全考试和现场工作视频，并采用问题识别、规则回忆、规则应用和规则结论 (IRAC) 的推理流程，全面评估推理能力。我们对 10 多个 LLM（包括基础模型、推理模型和多模态视觉模型）的不同提示策略进行了全面测试。结果显示，尽管当前 LLMs 表现良好，但其能力主要依赖语义匹配，而非基于 HSE 合规背景的原理性推理。此外，其原生推理轨迹缺乏严格的 HSE 合规评估所需的系统性法律推理。为缓解这些问题，我们提出了一种新的提示技术——专家推理 (RoE)，引导 LLMs 模拟不同专家的合规评估推理过程，以达成更准确的统一决策。我们希望通过本研究揭示 LLMs 在 HSE 合规评估中的推理差距，并激发相关任务的进一步研究。

> Health, Safety, and Environment (HSE) compliance assessment demands dynamic real-time decision-making under complicated regulations and complex human-machine-environment interactions. While large language models (LLMs) hold significant potential for decision intelligence and contextual dialogue, their capacity for domain-specific knowledge in HSE and structured legal reasoning remains underexplored. We introduce HSE-Bench, the first benchmark dataset designed to evaluate the HSE compliance assessment capabilities of LLM. HSE-Bench comprises over 1,000 manually curated questions drawn from regulations, court cases, safety exams, and fieldwork videos, and integrates a reasoning flow based on Issue spotting, rule Recall, rule Application, and rule Conclusion (IRAC) to assess the holistic reasoning pipeline. We conduct extensive evaluations on different prompting strategies and more than 10 LLMs, including foundation models, reasoning models and multimodal vision models. The results show that, although current LLMs achieve good performance, their capabilities largely rely on semantic matching rather than principled reasoning grounded in the underlying HSE compliance context. Moreover, their native reasoning trace lacks the systematic legal reasoning required for rigorous HSE compliance assessment. To alleviate these, we propose a new prompting technique, Reasoning of Expert (RoE), which guides LLMs to simulate the reasoning process of different experts for compliance assessment and reach a more accurate unified decision. We hope our study highlights reasoning gaps in LLMs for HSE compliance and inspires further research on related tasks.

[Arxiv](https://arxiv.org/abs/2505.22959)