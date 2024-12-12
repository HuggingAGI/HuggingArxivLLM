# COAT：实现内存高效 FP8 训练的优化器状态与激活压缩

发布时间：2024年10月25日

`其他` `模型训练` `内存优化`

> COAT: Compressing Optimizer states and Activation for Memory-Efficient FP8 Training

# 摘要

> FP8 训练已成为提升训练效率的颇具前景的方法。现有的框架将 FP8 计算用于线性层以加速训练，却把优化器状态和激活维持在更高精度，未能充分优化内存使用。本文引入了 COAT（用于 FP8 训练的压缩优化器状态和激活），这一新颖的 FP8 训练框架旨在训练大型模型时大幅降低内存占用。COAT 凭借两项关键创新解决了当前的局限：（1）动态范围扩展，让优化器状态分布与 FP8 表示范围更贴合，从而降低量化误差；（2）混合粒度激活量化，通过每张量和每组量化策略的结合来优化激活内存。实验表明，相较于 BF16，COAT 能将端到端训练的内存占用有效减少 1.54 倍，且在大型语言模型预训练和微调、视觉语言模型训练等各类任务中实现近乎无损的性能。与 BF16 相比，COAT 还实现了 1.43 倍的端到端训练加速，表现与 TransformerEngine 的加速相当甚至更优。COAT 能在更少的 GPU 上高效开展大型模型的全参数训练，并利于在分布式训练环境中将批处理大小翻倍，为大规模模型训练的扩展提供了切实可行的解决方案。代码可在 https://github.com/NVlabs/COAT 获取。

> FP8 training has emerged as a promising method for improving training efficiency. Existing frameworks accelerate training by applying FP8 computation to linear layers while leaving optimizer states and activations in higher precision, which fails to fully optimize memory usage. This paper introduces COAT (Compressing Optimizer States and Activations for FP8 Training), a novel FP8 training framework designed to significantly reduce memory footprint when training large models. COAT addresses current limitations through two key innovations: (1) Dynamic Range Expansion, which aligns optimizer state distributions more closely with the FP8 representation range, thereby reducing quantization error, and (2) Mixed-Granularity Activation Quantization, which optimizes activation memory using a combination of per-tensor and per-group quantization strategies. Experiments demonstrate that COAT effectively reduces end-to-end training memory footprint by 1.54x compared to BF16 while achieving nearly lossless performance across various tasks, such as Large Language Model pretraining and fine-tuning and Vision Language Model training. COAT also achieves a 1.43x end-to-end training speedup compared to BF16, performing on par with or surpassing TransformerEngine's speedup. COAT enables efficient full-parameter training of large models on fewer GPUs, and facilitates doubling the batch size in distributed training settings, providing a practical solution for scaling large-scale model training. The code is available at https://github.com/NVlabs/COAT.

[Arxiv](https://arxiv.org/abs/2410.19313)