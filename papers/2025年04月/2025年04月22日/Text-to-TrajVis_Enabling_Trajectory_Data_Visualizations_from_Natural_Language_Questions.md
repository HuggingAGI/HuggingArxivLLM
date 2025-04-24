# # Text-to-TrajVis：通过自然语言问题实现轨迹数据可视化

发布时间：2025年04月22日

`LLM应用` `数据可视化`

> Text-to-TrajVis: Enabling Trajectory Data Visualizations from Natural Language Questions

# 摘要

> 本文提出了文本到轨迹可视化（Text-to-TrajVis）任务，旨在将自然语言问题转化为轨迹数据可视化，从而为轨迹可视化系统开发自然语言接口提供支持。由于这是全新的任务，目前社区中尚未有相关数据集。为填补这一空白，我们首先设计了一种名为轨迹可视化语言（TVL）的新语言，用于更高效地查询轨迹数据并生成可视化。在此基础上，我们提出了一种结合大型语言模型（LLMs）与人工标注的数据集构建方法，以创建高质量的数据集。具体而言，我们通过系统化的过程生成 TVL，并利用 LLMs 为每个 TVL 标注对应的自然语言问题。这一方法构建了首个大规模的 Text-to-TrajVis 数据集——TrajVL，包含 18,140 个（问题，TVL）对。基于该数据集，我们系统评估了多个 LLMs（包括 GPT、Qwen、Llama 等）在该任务上的性能。实验结果表明，这一任务不仅可行，而且极具挑战性，值得研究界进一步深入探索。

> This paper introduces the Text-to-TrajVis task, which aims to transform natural language questions into trajectory data visualizations, facilitating the development of natural language interfaces for trajectory visualization systems. As this is a novel task, there is currently no relevant dataset available in the community. To address this gap, we first devised a new visualization language called Trajectory Visualization Language (TVL) to facilitate querying trajectory data and generating visualizations. Building on this foundation, we further proposed a dataset construction method that integrates Large Language Models (LLMs) with human efforts to create high-quality data. Specifically, we first generate TVLs using a comprehensive and systematic process, and then label each TVL with corresponding natural language questions using LLMs. This process results in the creation of the first large-scale Text-to-TrajVis dataset, named TrajVL, which contains 18,140 (question, TVL) pairs. Based on this dataset, we systematically evaluated the performance of multiple LLMs (GPT, Qwen, Llama, etc.) on this task. The experimental results demonstrate that this task is both feasible and highly challenging and merits further exploration within the research community.

[Arxiv](https://arxiv.org/abs/2504.16358)