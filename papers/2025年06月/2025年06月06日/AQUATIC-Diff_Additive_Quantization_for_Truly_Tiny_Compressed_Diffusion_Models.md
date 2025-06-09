# AQUATIC-Diff：为真正小巧的压缩扩散模型设计的加性量化方法

发布时间：2025年06月06日

`LLM应用` `生成模型` `模型压缩`

> AQUATIC-Diff: Additive Quantization for Truly Tiny Compressed Diffusion Models

# 摘要

> 扩散模型的商业化生成应用投入巨大，但其大众化应用仍受限于推理过程对硬件资源的极高要求。尽管针对扩散模型的量化策略有所突破，但研究主要集中在标量量化方法上。相比之下，向量量化方法在大型语言模型量化中表现优异。本研究将基于代码本的加法向量量化应用于扩散模型压缩。在标准的LDM-4图像分类基准测试中，我们的方法在20步推理时间内达到了极低比特权重量化的最优性能。值得注意的是，我们在W4A8配置下实现了比全精度模型低1.92的sFID值，并在W2A8配置下取得了FID、sFID和ISC的最佳报告结果。我们还通过高效推理内核实现了在任意硬件上的FLOPs节省，而不仅仅是依赖于小整数运算带来的节省，后者可能缺乏广泛硬件支持。

> Significant investments have been made towards the commodification of diffusion models for generation of diverse media. Their mass-market adoption is however still hobbled by the intense hardware resource requirements of diffusion model inference. Model quantization strategies tailored specifically towards diffusion models have been useful in easing this burden, yet have generally explored the Uniform Scalar Quantization (USQ) family of quantization methods. In contrast, Vector Quantization (VQ) methods, which operate on groups of multiple related weights as the basic unit of compression, have seen substantial success in Large Language Model (LLM) quantization. In this work, we apply codebook-based additive vector quantization to the problem of diffusion model compression. Our resulting approach achieves a new Pareto frontier for the extremely low-bit weight quantization on the standard class-conditional benchmark of LDM-4 on ImageNet at 20 inference time steps. Notably, we report sFID 1.92 points lower than the full-precision model at W4A8 and the best-reported results for FID, sFID and ISC at W2A8. We are also able to demonstrate FLOPs savings on arbitrary hardware via an efficient inference kernel, as opposed to savings resulting from small integer operations which may lack broad hardware support.

[Arxiv](https://arxiv.org/abs/2506.05960)