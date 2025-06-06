# 基于幂律的动态筛选方法，实现高效注意力机制

发布时间：2025年06月05日

`LLM应用` `计算机体系结构` `硬件优化`

> Power Law Guided Dynamic Sifting for Efficient Attention

# 摘要

> 在GPU上使用大型语言模型进行高效推理仍面临内存带宽限制的挑战，特别是在注意力计算过程中高带宽内存（HBM）与SRAM之间的数据传输。近似注意力方法通过减少计算和内存开销来应对这一挑战，但通常依赖昂贵的top-$k$操作，在GPU上表现不佳。我们提出了一种新型近似注意力方法SiftAttention，该方法用基于阈值的高效逐元素过滤操作替代top-$k$步骤。我们的直觉基于经验观察：注意力分数的$τ$分位数在序列生成步骤中遵循可预测的幂律分布。利用这一见解，我们的方法在每一步生成过程中动态估计每个提示的阈值。仅加载/使用高于该阈值的注意力分数及其对应的价值向量来计算注意力输出，从而减少HBM与SRAM之间的数据移动。我们的评估表明，与现有的近似注意力方法相比，SiftAttention在降低加载价值向量时的内存带宽使用的同时，能更好地保持模型质量。

> Efficient inference on GPUs using large language models remains challenging due to memory bandwidth limitations, particularly during data transfers between High Bandwidth Memory (HBM) and SRAM in attention computations. Approximate attention methods address this issue by reducing computational and memory overhead but often rely on expensive top-$k$ operations, which perform poorly on GPUs. We propose SiftAttention, a novel approximate attention method that replaces the top-$k$ step with a computationally efficient element-wise filtering operation based on a threshold value. Our intuition for doing this is based on our empirical observation that the $τ$-th quantile of attention scores follows a predictable power-law over sequential generation steps. Exploiting this insight, our approach dynamically estimates a threshold value per prompt at each generation step. Only attention scores above this threshold and their corresponding value vectors are loaded/used to compute the attention output, reducing data movement between HBM and SRAM. Our evaluation demonstrates that SiftAttention preserves model quality better than existing approximate attention methods while reducing memory bandwidth usage when loading value vectors.

[Arxiv](https://arxiv.org/abs/2506.05300)