# 大型语言模型量化技术的全面评估

发布时间：2025年07月23日

`LLM理论` `模型优化` `量化技术`

> A Comprehensive Evaluation on Quantization Techniques for Large Language Models

# 摘要

> 对于大型语言模型（LLMs），后训练量化（PTQ）能大幅减少内存占用和计算成本。模型量化领域发展迅速，尽管已有许多研究展示了突破性成果，但因量化方法通常包含多个组件，这些研究可能未在同一基准下进行实验。此外，理解现有方法间的理论联系至关重要。为此，我们全面回顾了前沿量化方法，并在同一基准上进行详尽评估，确保公平对比。据我们所知，这种全面而公平的研究仍具重要意义且尚未充分展开。

为深入理解量化方法的内在联系，我们将现有方法分解为预量化变换和量化误差缓解两大步骤。预量化变换旨在通过预处理减少异常值影响，使数据分布更平坦，更适合量化。量化误差缓解则通过技术手段抵消量化过程中的误差，提升模型性能。我们评估了不同量化组件的影响，并分析了最新MXFP4格式的表现。

实验结果表明，优化的旋转与缩放策略在预量化变换中表现最佳，而结合低秩补偿与GPTQ的方案在缓解量化误差方面优于单独使用GPTQ。此外，我们发现INT4的最佳预量化策略并不适用于MXFP4，这一发现为未来研究提供了重要方向。


> For large language models (LLMs), post-training quantization (PTQ) can significantly reduce memory footprint and computational overhead. Model quantization is a rapidly evolving research field. Though many papers have reported breakthrough performance, they may not conduct experiments on the same ground since one quantization method usually contains multiple components. In addition, analyzing the theoretical connections among existing methods is crucial for in-depth understanding. To bridge these gaps, we conduct an extensive review of state-of-the-art methods and perform comprehensive evaluations on the same ground to ensure fair comparisons. To our knowledge, this fair and extensive investigation remains critically important yet underexplored. To better understand the theoretical connections, we decouple the published quantization methods into two steps: pre-quantization transformation and quantization error mitigation. We define the former as a preprocessing step applied before quantization to reduce the impact of outliers, making the data distribution flatter and more suitable for quantization. Quantization error mitigation involves techniques that offset the errors introduced during quantization, thereby enhancing model performance. We evaluate and analyze the impact of different components of quantization methods. Additionally, we analyze and evaluate the latest MXFP4 data format and its performance. Our experimental results demonstrate that optimized rotation and scaling yield the best performance for pre-quantization transformation, and combining low-rank compensation with GPTQ occasionally outperforms using GPTQ alone for quantization error mitigation. Furthermore, we explore the potential of the latest MXFP4 quantization and reveal that the optimal pre-quantization transformation strategy for INT4 does not generalize well to MXFP4, inspiring further investigation.

[Arxiv](https://arxiv.org/abs/2507.17417)