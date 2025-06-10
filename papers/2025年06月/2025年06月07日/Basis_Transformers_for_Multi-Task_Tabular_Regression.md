# 基变换器在多任务表格回归中的应用

发布时间：2025年06月07日

`其他` `表格数据处理` `机器学习`

> Basis Transformers for Multi-Task Tabular Regression

# 摘要

> 处理表格数据面临诸多挑战，包括信息不完整、噪声干扰以及数据结构异构。现有技术往往难以同时处理表格数据的关键方面，例如文本信息、可变数量的列以及缺乏元数据的未见数据。为此，我们提出了一种新颖的架构——	extit{基础变换器}，专门设计用于应对这些挑战，同时尊重表格数据中的固有不变性，如层级结构和数值表示。我们在一个多任务表格回归基准上评估了我们的设计，在OpenML-CTR23基准的34项任务中，中位$R^2$分数提高了0.338，标准差最低。此外，我们的模型参数数量仅为最佳表现基线的五分之一，并且超越了预训练的大语言模型基线——即使是从随机初始化的权重开始。


> Dealing with tabular data is challenging due to partial information, noise, and heterogeneous structure. Existing techniques often struggle to simultaneously address key aspects of tabular data such as textual information, a variable number of columns, and unseen data without metadata besides column names. We propose a novel architecture, \textit{basis transformers}, specifically designed to tackle these challenges while respecting inherent invariances in tabular data, including hierarchical structure and the representation of numeric values. We evaluate our design on a multi-task tabular regression benchmark, achieving an improvement of 0.338 in the median $R^2$ score and the lowest standard deviation across 34 tasks from the OpenML-CTR23 benchmark. Furthermore, our model has five times fewer parameters than the best-performing baseline and surpasses pretrained large language model baselines -- even when initialized from randomized weights.

[Arxiv](https://arxiv.org/abs/2506.06926)