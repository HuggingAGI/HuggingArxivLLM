# QuEST: 通过1位权重和激活实现大型语言模型的稳定训练

发布时间：2025年02月07日

`LLM理论` `模型压缩` `量化技术`

> QuEST: Stable Training of LLMs with 1-Bit Weights and Activations

# 摘要

> 减少大型语言模型 (LLMs) 的巨额成本，量化或稀疏表示的训练或部署是一个有效途径。尽管后训练压缩方法广受欢迎，但通过量化感知训练 (QAT) 直接在这些表示上训练以获得更精确的压缩模型的问题仍未完全解决：例如，近期研究 (arXiv:2411.04330v2) 将使用 QAT 的“最优”位宽定为 8 位权重和激活，同时保持与标准 FP16/BF16 精度相当的准确性。
    我们提出了一种名为 QuEST 的新方法，该方法在 FP16 的帕累托竞争中表现优异，即在较小的模型规模下提供更高的准确性，同时使用 4 位或更少的权重和激活训练模型。此外，QuEST 允许使用 1 位权重和激活进行稳定训练。QuEST 通过以下两个关键改进实现这一目标：(1) 通过 Hadamard 归一化和 MSE 最优拟合，准确且快速地量化权重和激活的（连续）分布；(2) 基于显式最小化量化状态下计算的噪声梯度与“真实”（但未知）全精度梯度之间误差的新信任梯度估计器。在 Llama 类架构上的实验表明，QuEST 在整个硬件支持的精度范围内诱导稳定的缩放定律，并可以扩展到稀疏表示。我们提供了 GPU 内核支持，表明 QuEST 生成的模型可以高效执行。我们的代码可在 https://github.com/IST-DASLab/QuEST 获取。

> One approach to reducing the massive costs of large language models (LLMs) is the use of quantized or sparse representations for training or deployment. While post-training compression methods are very popular, the question of obtaining even more accurate compressed models by directly training over such representations, i.e., Quantization-Aware Training (QAT), is still open: for example, a recent study (arXiv:2411.04330v2) put the "optimal" bit-width at which models can be trained using QAT, while staying accuracy-competitive with standard FP16/BF16 precision, at 8-bits weights and activations.
  We advance this state-of-the-art via a new method called QuEST, which is Pareto-competitive with FP16, i.e., it provides better accuracy at lower model size, while training models with weights and activations in 4-bits or less. Moreover, QuEST allows stable training with 1-bit weights and activations. QuEST achieves this by improving two key aspects of QAT methods: (1) accurate and fast quantization of the (continuous) distributions of weights and activations via Hadamard normalization and MSE-optimal fitting; (2) a new trust gradient estimator based on the idea of explicitly minimizing the error between the noisy gradient computed over quantized states and the "true" (but unknown) full-precision gradient. Experiments on Llama-type architectures show that QuEST induces stable scaling laws across the entire range of hardware-supported precisions, and can be extended to sparse representations. We provide GPU kernel support showing that models produced by QuEST can be executed efficiently. Our code is available at https://github.com/IST-DASLab/QuEST.

[Arxiv](https://arxiv.org/abs/2502.05003)