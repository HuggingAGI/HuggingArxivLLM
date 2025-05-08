# # 高效量化模型微调：通过自适应秩和位宽实现

发布时间：2025年05月02日

`LLM理论` `人工智能` `模型优化`

> Efficient Fine-Tuning of Quantized Models via Adaptive Rank and Bitwidth

# 摘要

> QLoRA 将低比特量化与 LoRA 有机结合，为大语言模型的内存友好微调提供了有效解决方案。然而，近期基于 SVD 的连续更新迭代方法在初始化 LoRA 矩阵以适应量化误差时，大多未能显著提升性能。动态混合精度作为一种优化思路，旨在持续提升量化模型的微调效果，但现有方法往往割裂地优化低秩子空间或量化组件，忽视了它们之间的协同作用。针对这一问题，我们提出了一种全新的解决方案——	extbf{QR-Adaptor}。这是一种统一且无需梯度的策略，通过利用部分校准数据，同步优化各层的量化组件和低秩空间秩值，从而实现模型性能的持续提升。与传统方法不同，QR-Adaptor 并不直接追求量化误差的最小化，而是将精度和秩分配视为一个由实际下游性能和内存使用情况共同指导的离散优化问题。实验结果显示，相较于现有的量化 LoRA 微调方法，我们的方法在 GSM8K 数据集上实现了 4.89\% 的准确率提升，部分场景下甚至超越了 16-bit 微调模型的性能，同时保持了 4-bit 设置的内存效率。

> QLoRA effectively combines low-bit quantization and LoRA to achieve memory-friendly fine-tuning for large language models (LLM). Recently, methods based on SVD for continuous update iterations to initialize LoRA matrices to accommodate quantization errors have generally failed to consistently improve performance. Dynamic mixed precision is a natural idea for continuously improving the fine-tuning performance of quantized models, but previous methods often optimize low-rank subspaces or quantization components separately, without considering their synergy. To address this, we propose \textbf{QR-Adaptor}, a unified, gradient-free strategy that uses partial calibration data to jointly search the quantization components and the rank of low-rank spaces for each layer, thereby continuously improving model performance. QR-Adaptor does not minimize quantization error but treats precision and rank allocation as a discrete optimization problem guided by actual downstream performance and memory usage. Compared to state-of-the-art (SOTA) quantized LoRA fine-tuning methods, our approach achieves a 4.89\% accuracy improvement on GSM8K, and in some cases even outperforms the 16-bit fine-tuned model while maintaining the memory footprint of the 4-bit setting.

[Arxiv](https://arxiv.org/abs/2505.03802)