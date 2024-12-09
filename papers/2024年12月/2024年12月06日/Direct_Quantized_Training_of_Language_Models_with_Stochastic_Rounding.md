# 语言模型的直接量化训练与随机舍入

发布时间：2024年12月06日

`LLM应用` `人工智能` `模型训练`

> Direct Quantized Training of Language Models with Stochastic Rounding

# 摘要

> 尽管像 BitNet 这样的近期量化大型语言模型（LLMs）已为部署时大幅降低内存使用量开辟了道路，采用了二进制或三进制权重，但训练此类模型仍需大量内存。这在一定程度上是因为直通估计所需的高精度（即未量化）权重矩阵在整个训练过程中都得保留。为应对此问题，我们探索了在反向传播时不依赖直通估计器直接更新量化的低精度权重矩阵的可能性，以节省训练期间的内存使用。具体而言，我们运用随机舍入技术，将整个训练中因使用低位权重导致的信息损失降到最低。在我们基于 LLaMA 结构的模型上的实验结果显示：（1）即便低精度权重被限制为三进制值，仅用低精度权重训练也是可行的；（2）将位宽拓展至 8 位时，与 BitNet b1.58 相比仅出现 5％的损失降级，同时在训练时具备减少内存使用的潜力；（3）我们的模型还能使用三进制权重进行推理，展现出其在部署中的灵活性。

> Although recent quantized Large Language Models (LLMs), such as BitNet, have paved the way for significant reduction in memory usage during deployment with binary or ternary weights, training these models still demands substantial memory footprints. This is partly because high-precision (i.e., unquantized) weight matrices required for straight-through estimation must be maintained throughout the whole training process. To address this, we explore the potential of directly updating the quantized low-precision weight matrices without relying on the straight-through estimator during backpropagation, thereby saving memory usage during training. Specifically, we employ a stochastic rounding technique to minimize information loss caused by the use of low-bit weights throughout training. Experimental results on our LLaMA-structured models indicate that (1) training with only low-precision weights is feasible even when they are constrained to ternary values, (2) extending the bit width to 8 bits results in only a 5% loss degradation compared to BitNet b1.58 while offering the potential for reduced memory usage during training, and (3) our models can also perform inference using ternary weights, showcasing their flexibility in deployment.

[Arxiv](https://arxiv.org/abs/2412.04787)