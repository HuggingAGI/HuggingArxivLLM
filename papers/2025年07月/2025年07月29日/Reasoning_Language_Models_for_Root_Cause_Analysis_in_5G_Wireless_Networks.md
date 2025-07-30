# 5G无线网络根本原因分析推理语言模型

发布时间：2025年07月29日

`LLM应用` `网络运维`

> Reasoning Language Models for Root Cause Analysis in 5G Wireless Networks

# 摘要

> 移动网络中的根本原因分析（RCA）面临多重挑战，包括可解释性、领域专业知识和因果推理能力的需求。本研究提出了一种基于大型语言模型（LLMs）的轻量级RCA框架。我们创建了TeleLogs数据集，这是一个专门设计用于评估RCA能力的标注故障问题集合。实验结果表明，现有的开源推理型LLMs在处理这些任务时表现欠佳，凸显了领域特定适配的重要性。为解决这一问题，我们提出了一种结合监督微调与强化学习的两阶段训练方法，旨在提升LLMs的准确性和推理质量。该方法通过微调RCA模型，将领域知识融入其中，并生成结构化的多步骤诊断解释，显著提升了可解释性和实际效果。在多个规模的LLMs上进行的广泛测试表明，与现有推理型和非推理型模型相比，我们的方法实现了显著的性能提升，包括在随机化测试变体上的强泛化能力。这表明，领域适配且推理增强的LLMs在实际网络运维与管理中的RCA应用具有巨大潜力。

> Root Cause Analysis (RCA) in mobile networks remains a challenging task due to the need for interpretability, domain expertise, and causal reasoning. In this work, we propose a lightweight framework that leverages Large Language Models (LLMs) for RCA. To do so, we introduce TeleLogs, a curated dataset of annotated troubleshooting problems designed to benchmark RCA capabilities. Our evaluation reveals that existing open-source reasoning LLMs struggle with these problems, underscoring the need for domain-specific adaptation. To address this issue, we propose a two-stage training methodology that combines supervised fine-tuning with reinforcement learning to improve the accuracy and reasoning quality of LLMs. The proposed approach fine-tunes a series of RCA models to integrate domain knowledge and generate structured, multi-step diagnostic explanations, improving both interpretability and effectiveness. Extensive experiments across multiple LLM sizes show significant performance gains over state-of-the-art reasoning and non-reasoning models, including strong generalization to randomized test variants. These results demonstrate the promise of domain-adapted, reasoning-enhanced LLMs for practical and explainable RCA in network operation and management.

[Arxiv](https://arxiv.org/abs/2507.21974)