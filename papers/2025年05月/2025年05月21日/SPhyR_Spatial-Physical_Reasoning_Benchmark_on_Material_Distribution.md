# SPhyR：针对材料分布的空间物理推理基准测试

发布时间：2025年05月21日

`LLM应用`

> SPhyR: Spatial-Physical Reasoning Benchmark on Material Distribution

# 摘要

> 我们推出了一款全新的数据集，通过拓扑优化这一技术，评估大型语言模型（LLM）在物理和空间推理方面的表现。拓扑优化是一种在给定载荷和支撑条件下计算设计空间内最优材料分布的方法。在本数据集中，LLMs将接收包括2D边界、施加的力和支撑等条件，并需据此推理出最优的材料分布。数据集涵盖了多种任务，从填补结构中缺失的区域到预测完整的材料分布。完成这些任务需要模型在给定约束条件下理解力的流动和所需材料分布，而无需依赖仿真工具或显式物理模型，这对模型的结构稳定性和空间组织推理能力提出了挑战。我们的数据集专注于评估二维环境下的空间和物理推理能力，为传统语言和逻辑基准提供了全新的补充视角。

> We introduce a novel dataset designed to benchmark the physical and spatial reasoning capabilities of Large Language Models (LLM) based on topology optimization, a method for computing optimal material distributions within a design space under prescribed loads and supports. In this dataset, LLMs are provided with conditions such as 2D boundary, applied forces and supports, and must reason about the resulting optimal material distribution. The dataset includes a variety of tasks, ranging from filling in masked regions within partial structures to predicting complete material distributions. Solving these tasks requires understanding the flow of forces and the required material distribution under given constraints, without access to simulation tools or explicit physical models, challenging models to reason about structural stability and spatial organization. Our dataset targets the evaluation of spatial and physical reasoning abilities in 2D settings, offering a complementary perspective to traditional language and logic benchmarks.

[Arxiv](https://arxiv.org/abs/2505.16048)