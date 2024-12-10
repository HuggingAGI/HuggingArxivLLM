# 精通协作式多模态数据选择：聚焦信息性、独特性与代表性

发布时间：2024年12月09日

`LLM应用` `多模态` `语言模型`

> Mastering Collaborative Multi-modal Data Selection: A Focus on Informativeness, Uniqueness, and Representativeness

# 摘要

> 指令调优用于对预训练的多模态大型语言模型（MLLMs）进行微调，以应对现实世界的任务。然而，视觉指令数据集的快速扩张带来了数据冗余，致使计算成本过高。我们提出了一个名为 DataTailor 的协作框架，它借助信息性、独特性和代表性这三个关键原则来进行有效的数据筛选。我们主张，有价值的样本应当对任务具有信息量、不冗余并且能代表样本分布（即不是离群值）。我们还进一步提出了针对每个原则的实用评分方法，能够自动适应给定的数据集，无需繁琐的超参数调试。在各类基准上的综合实验显示，DataTailor 仅用 15%的数据就实现了全数据微调性能的 100.8%，在大幅降低计算成本的同时保持了出色的结果。这充分诠释了 MLLM 开发中“少即是多”的理念。

> Instruction tuning fine-tunes pre-trained Multi-modal Large Language Models (MLLMs) to handle real-world tasks. However, the rapid expansion of visual instruction datasets introduces data redundancy, leading to excessive computational costs. We propose a collaborative framework, DataTailor, which leverages three key principles--informativeness, uniqueness, and representativeness--for effective data selection. We argue that a valuable sample should be informative of the task, non-redundant, and represent the sample distribution (i.e., not an outlier). We further propose practical ways to score against each principle, which automatically adapts to a given dataset without tedious hyperparameter tuning. Comprehensive experiments on various benchmarks demonstrate that DataTailor achieves 100.8% of the performance of full-data fine-tuning with only 15% of the data, significantly reducing computational costs while maintaining superior results. This exemplifies the "Less is More" philosophy in MLLM development.

[Arxiv](https://arxiv.org/abs/2412.06293)