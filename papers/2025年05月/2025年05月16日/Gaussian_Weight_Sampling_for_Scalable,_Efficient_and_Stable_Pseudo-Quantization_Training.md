# 高斯权重采样助力大规模、高效稳定的伪量化训练

发布时间：2025年05月16日

`LLM理论` `机器学习` `计算机系统优化`

> Gaussian Weight Sampling for Scalable, Efficient and Stable Pseudo-Quantization Training

# 摘要

> 随着大型语言模型 (LLMs) 规模的不断扩大，对更高效率的追求促使全量化训练 (FQT) 逐渐取代了 BF16 的地位。尽管 FQT 能够加速训练，但它面临一致性问题，并且需要在指数级数量的案例中进行搜索，每个案例都需要超过 200B 个令牌来确保稳定性。
    伪量化训练 (PQT) 为 FQT 的问题提供了有效解决方案，尽管其潜力尚未被充分挖掘。我们深入探讨了 PQT 的实际应用，并提出了一种与浮点数 (FP) 友好的噪声分布【数学公式】，其特性包括随机精度退火。因此，我们提出的方法通过 PQT 为低精度 FP 参数提供了一个有效的理论基础，利用加法和后续 FP 转换实现了高效的伪量化。
    我们发现，高斯权重采样具有以下优势：
    - **可扩展性**：支持低精度 FP 参数（低至 FP6）和高精度噪声（高达 9 位）与 BF16 操作器。
    - **高效性**：在 A100 GPU 上，Llama2 训练每秒处理的令牌数仅带来 1.40% 的计算开销，并且在 GPU 内存中每个参数仅需 2 字节。
    - **稳定性**：在预训练 GPT2 和 Llama2 模型（参数量高达 1B，令牌量高达 300B）时，其性能与 BF16 基线持平甚至超越。
    结果表明，结合高斯权重采样的 PQT 在大规模模型训练中表现优异，为低精度训练提供了一种高效稳定的解决方案。

> Ever-growing scale of large language models (LLMs) is pushing for improved efficiency, favoring fully quantized training (FQT) over BF16. While FQT accelerates training, it faces consistency challenges and requires searching over an exponential number of cases, each needing over 200B tokens to ensure stability.
  Pseudo-quantization training (PQT) addresses the issues of FQT, although it is not well-studied. We explore the practical implications of PQT in detail and propose a noise distribution $R$ that is floating-point (FP)-friendly, with ideal properties including stochastic precision annealing. As a result, the proposed method serves as an effective theoretical foundation for low-precision FP parameters through PQT, utilizing efficient fake quantization via an addition and subsequent FP casting.
  We demonstrate that Gaussian weight sampling is (1) scalable: supports low-precision FP parameters down to FP6 and high-precision noise up to 9-bit with BF16 operator. The proposed method is (2) efficient: incurring computational overhead as low as 1.40\% on the A100 GPU in terms of Llama2 training tokens per second, and requiring 2 bytes per parameter in GPU memory. We demonstrate that PQT with Gaussian weight sampling is (3) stable: closely following or even surpassing performance of the BF16 baseline while pre-training GPT2 and Llama2 models with up to 1B parameters and 300B tokens.

[Arxiv](https://arxiv.org/abs/2505.11170)