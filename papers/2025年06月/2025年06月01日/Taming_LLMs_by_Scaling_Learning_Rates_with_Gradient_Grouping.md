# 通过梯度分组缩放学习率，驯服大型语言模型

发布时间：2025年06月01日

`LLM理论` `人工智能` `机器学习`

> Taming LLMs by Scaling Learning Rates with Gradient Grouping

# 摘要

> 训练大型语言模型 (LLMs) 因其规模庞大和架构异构而面临诸多挑战。尽管自适应优化器如 AdamW 在一定程度上缓解了梯度变化的问题，但它们在有效且高效地估计参数级学习率方面仍存在局限性，导致训练不稳定、收敛速度慢，并且与参数高效微调 (PEFT) 技术的兼容性不佳。本研究提出了一种名为基于梯度分组的缩放方法 (SGG) 的优化器包装器，通过动态分组和组特定缩放来改进自适应学习率估计。SGG 首先将每一层的梯度统计信息聚类，然后应用特定于每个聚类的缩放来校准每个参数的学习率，从而在保持精确的每参数自适应的同时，施加集体组级约束。在多样化 (M)LLM 基准上的实验表明，SGG 与现有优化器无缝集成，并在各种模型规模下提供一致的性能提升和比基线更快的收敛速度。其在不同批量大小和学习率下的稳定性确立了 SGG 作为 LLM 优化的稳健选择。

> Training large language models (LLMs) poses challenges due to their massive scale and heterogeneous architectures. While adaptive optimizers like AdamW help address gradient variations, they still struggle with efficient and effective parameter-wise learning rate estimation, resulting in training instability, slow convergence, and poor compatibility with parameter-efficient fine-tuning (PEFT) techniques. This work introduces Scaling with Gradient Grouping (SGG), an optimizer wrapper that improves adaptive learning rate estimation by dynamic grouping and group-specific scaling. SGG first groups gradient statistics in each layer into clusters and then applies cluster-specific scaling to calibrate learning rates for each parameter, thus imposing collective group-wise constraints while maintaining precise per-parameter adaptation. Experiments on diverse (M)LLM benchmarks show that SGG integrates seamlessly with existing optimizers, and offers consistent gains and faster convergence over baselines, with various model sizes. Its stability across varying batch sizes and learning rates establishes SGG as a robust choice for LLM optimization.

[Arxiv](https://arxiv.org/abs/2506.01049)