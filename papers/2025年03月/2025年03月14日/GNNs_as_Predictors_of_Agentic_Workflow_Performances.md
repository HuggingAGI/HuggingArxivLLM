# GNN：智能体工作流性能的预测器

发布时间：2025年03月14日

`Agent` `人工智能` `自动化`

> GNNs as Predictors of Agentic Workflow Performances

# 摘要

> 大型语言模型（LLMs）驱动的智能体工作流程在处理复杂任务方面表现卓越。然而，实际应用中优化这些工作流程因频繁调用LLMs而成本高昂且效率低下。本立场论文提出将智能体工作流程建模为计算图，并主张使用图神经网络（GNNs）作为高效预测器，从而避免重复调用LLMs进行评估。为实证这一观点，我们构建了FLORA-Bench，一个统一的平台，用于评估GNNs在预测智能体工作流程性能方面的表现。通过大量实验，我们得出结论：GNNs是简单而有效的预测工具。这一发现不仅为GNNs开辟了新应用领域，还为智能体工作流程的自动优化提供了全新方向。所有代码、模型和数据均可在GitHub仓库https://github.com/youngsoul0731/Flora-Bench获取。

> Agentic workflows invoked by Large Language Models (LLMs) have achieved remarkable success in handling complex tasks. However, optimizing such workflows is costly and inefficient in real-world applications due to extensive invocations of LLMs. To fill this gap, this position paper formulates agentic workflows as computational graphs and advocates Graph Neural Networks (GNNs) as efficient predictors of agentic workflow performances, avoiding repeated LLM invocations for evaluation. To empirically ground this position, we construct FLORA-Bench, a unified platform for benchmarking GNNs for predicting agentic workflow performances. With extensive experiments, we arrive at the following conclusion: GNNs are simple yet effective predictors. This conclusion supports new applications of GNNs and a novel direction towards automating agentic workflow optimization. All codes, models, and data are available at https://github.com/youngsoul0731/Flora-Bench.

[Arxiv](https://arxiv.org/abs/2503.11301)