# 一阶误差的重要性：量化大型语言模型的精确补偿方法

发布时间：2025年07月15日

`LLM应用

摘要讨论了后训练量化（PTQ）在压缩大型语言模型中的应用，提出了一种改进的方法FOEM，以提高模型的性能和效率。这属于LLM应用的范畴，因为它专注于实际应用中的优化和模型压缩技术。` `模型压缩` `模型优化`

> First-Order Error Matters: Accurate Compensation for Quantized Large Language Models

# 摘要

> 后训练量化 (PTQ) 为压缩大型语言模型 (LLMs) 提供了一种高效的方法，大幅降低了内存访问和计算成本。现有基于补偿的权重校准方法通常依赖二阶泰勒展开建模量化误差，假设一阶项在良好训练的全精度模型中可忽略不计。然而，我们发现逐步补偿过程会在潜在权重与其全精度对应物之间引入累积的一阶偏差，使得这一假设从根本上存在缺陷。为此，我们提出了 FOEM，一种新型 PTQ 方法，显式地将一阶梯度项纳入量化误差补偿。FOEM 通过直接计算潜在权重与全精度权重之间的差异来近似梯度，避免了基于反向传播的梯度计算的高成本和有限的泛化能力。这种方法引入了极小的额外计算开销。此外，FOEM 利用预计算的 Cholesky 因子实时高效地恢复 Hessian 子矩阵的逆。在广泛应用于各种模型和基准测试的实验中，FOEM 一致优于经典的 GPTQ 方法。在 3-bit 权重量化中，FOEM 将 Llama3-8B 的困惑度降低了 89.6%，并将 Llama3-70B 的 5-shot MMLU 准确率从 51.7% 提高到 74.9%，接近全精度性能的 78.6%。此外，FOEM 可以无缝集成到高级技术如 GPTAQ 和 SpinQuant 中，在具有挑战性的 W4A4KV4 设置下进一步提升性能，并缩小与全精度基线的准确率差距，超越当前最先进方法的水平。代码可在 https://github.com/Xingyu-Zheng/FOEM 获取。

> Post-training quantization (PTQ) offers an efficient approach to compressing large language models (LLMs), significantly reducing memory access and computational costs. Existing compensation-based weight calibration methods often rely on a second-order Taylor expansion to model quantization error, under the assumption that the first-order term is negligible in well-trained full-precision models. However, we reveal that the progressive compensation process introduces accumulated first-order deviations between latent weights and their full-precision counterparts, making this assumption fundamentally flawed. To address this, we propose FOEM, a novel PTQ method that explicitly incorporates first-order gradient terms to improve quantization error compensation. FOEM approximates gradients by directly computing the difference between latent and full-precision weights, avoiding the high cost and limited generalization of backpropagation-based gradient computation. This approach introduces minimal additional computational overhead. Moreover, FOEM leverages precomputed Cholesky factors to efficiently recover the inverse of Hessian submatrices in real time. Extensive experiments across a wide range of models and benchmarks demonstrate that FOEM consistently outperforms the classical GPTQ method. In 3-bit weight-only quantization, FOEM reduces the perplexity of Llama3-8B by 89.6%, and improves the 5-shot MMLU accuracy of Llama3-70B from 51.7% to 74.9%, approaching the full-precision performance of 78.6%. Furthermore, FOEM can be seamlessly integrated with advanced techniques such as GPTAQ and SpinQuant, yielding additional improvements under the challenging W4A4KV4 setting, and further narrowing the accuracy gap with full-precision baselines beyond what current state-of-the-art methods achieve. The code is available at https://github.com/Xingyu-Zheng/FOEM.

[Arxiv](https://arxiv.org/abs/2507.11017)