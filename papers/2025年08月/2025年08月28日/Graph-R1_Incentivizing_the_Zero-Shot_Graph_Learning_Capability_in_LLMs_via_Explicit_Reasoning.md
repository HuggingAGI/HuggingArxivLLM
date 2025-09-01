# Graph-R1：通过显式推理激发LLMs的零样本图学习能力

发布时间：2025年08月28日

`强化学习` `基础理论`

> Graph-R1: Incentivizing the Zero-Shot Graph Learning Capability in LLMs via Explicit Reasoning

# 摘要

> 在缺乏特定任务监督时，泛化到未见过的图任务依然颇具挑战。图神经网络（GNNs）受限于固定标签空间，大型语言模型（LLMs）则缺乏结构归纳偏置。而大型推理模型（LRMs）的最新进展借助显式、长链思维推理，提供了零样本解决方案。受此启发，我们提出一种无GNN方法，将图任务（节点分类、链路预测、图分类）重新表述为可由LRMs解决的文本推理问题。我们首次引入了包含这些任务详细推理轨迹的数据集，并开发了Graph-R1——一个强化学习框架，该框架利用特定任务的反思模板引导对线性化图的推理。实验表明，Graph-R1在零样本场景下性能超越现有最优基线，能生成可解释且有效的预测。我们的研究凸显了显式推理在图学习中的应用前景，并为未来研究提供了新资源。

> Generalizing to unseen graph tasks without task-pecific supervision remains challenging. Graph Neural Networks (GNNs) are limited by fixed label spaces, while Large Language Models (LLMs) lack structural inductive biases. Recent advances in Large Reasoning Models (LRMs) provide a zero-shot alternative via explicit, long chain-of-thought reasoning. Inspired by this, we propose a GNN-free approach that reformulates graph tasks--node classification, link prediction, and graph classification--as textual reasoning problems solved by LRMs. We introduce the first datasets with detailed reasoning traces for these tasks and develop Graph-R1, a reinforcement learning framework that leverages task-specific rethink templates to guide reasoning over linearized graphs. Experiments demonstrate that Graph-R1 outperforms state-of-the-art baselines in zero-shot settings, producing interpretable and effective predictions. Our work highlights the promise of explicit reasoning for graph learning and provides new resources for future research.

[Arxiv](https://arxiv.org/abs/2508.17387)