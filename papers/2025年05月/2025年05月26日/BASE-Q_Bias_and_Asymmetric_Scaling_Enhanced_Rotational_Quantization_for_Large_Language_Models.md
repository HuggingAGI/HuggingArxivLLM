# # 偏置与非对称缩放增强的旋转量化方法：BASE-Q在大型语言模型中的应用

发布时间：2025年05月26日

`LLM理论` `人工智能` `模型优化`

> BASE-Q: Bias and Asymmetric Scaling Enhanced Rotational Quantization for Large Language Models

# 摘要

> 旋转已成为大型语言模型 (LLMs) 最先进的量化流水线的关键技术，通过有效平滑权重和激活中的异常值。然而，进一步优化旋转参数仅能带来有限性能提升，同时引入显著训练开销：由于旋转参数共享，必须同时加载整个模型以启用反向传播，导致大量内存消耗和有限的实际效用。本研究识别出当前旋转量化方法的两个根本限制：(i) 旋转未能对齐通道均值，导致更宽泛的量化范围和增加的舍入误差；(ii) 旋转使激活分布更趋近于高斯分布，增加了由裁剪误差导致的能量损失。为解决这些问题，我们引入了	extbf{BASE-Q}，一种简单而强大的方法，结合偏差校正和非对称缩放，有效减少舍入和裁剪误差。此外，BASE-Q支持块级优化，无需内存密集型的全模型反向传播。在各种 LLM 和基准测试中的广泛实验表明，BASE-Q 的有效性显著，与 QuaRot、SpinQuant 和 OSTQuant 相比，分别将准确率差距缩小了 50.5%、42.9% 和 29.2%。代码即将发布。

> Rotations have become essential to state-of-the-art quantization pipelines for large language models (LLMs) by effectively smoothing outliers in weights and activations. However, further optimizing the rotation parameters offers only limited performance gains and introduces significant training overhead: due to rotation parameter sharing, full-model must be loaded simultaneously to enable backpropagation, resulting in substantial memory consumption and limited practical utility. In this work, we identify two fundamental limitations of current rotational quantization methods: (i) rotation fails to align channel means, resulting in wider quantization bounds and increased rounding errors; and (ii) rotation makes the activation distribution more Gaussian-like, increasing energy loss caused by clipping errors. To address these issues, we introduce \textbf{BASE-Q}, a simple yet powerful approach that combines bias correction and asymmetric scaling to effectively reduce rounding and clipping errors. Furthermore, BASE-Q enables blockwise optimization, eliminating the need for memory-intensive full-model backpropagation. Extensive experiments on various LLMs and benchmarks demonstrate the effectiveness of BASE-Q, narrowing the accuracy gap to full-precision models by 50.5\%, 42.9\%, and 29.2\% compared to QuaRot, SpinQuant, and OSTQuant, respectively. The code will be released soon.

[Arxiv](https://arxiv.org/abs/2506.15689)