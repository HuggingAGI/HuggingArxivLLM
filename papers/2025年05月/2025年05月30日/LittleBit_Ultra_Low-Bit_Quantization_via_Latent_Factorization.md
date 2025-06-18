# LittleBit：超低比特量化新突破，通过潜在因子分解实现

发布时间：2025年05月30日

`LLM理论` `人工智能` `模型优化`

> LittleBit: Ultra Low-Bit Quantization via Latent Factorization

# 摘要

> 部署大型语言模型（LLMs）时，常常面临巨大的内存和计算成本挑战。量化技术看似提供了解决方案，但在低于1比特的压缩领域，性能下降的问题依然棘手。本文介绍了一种名为LittleBit的全新极端LLM压缩方法，针对0.1比特每权重（BPW）级别，实现了近31【数学公式】倍的内存缩减，例如将Llama2-13B压缩至0.9GB以下。LittleBit通过潜在矩阵分解将权重表示为低秩形式，随后对这些分解因子进行二值化处理。为了弥补这种极端精度带来的信息损失，该方法引入了一种多尺度补偿机制，包括行、列以及额外的按秩重要性学习的潜在维度。LittleBit的两大关键创新使其在训练过程中表现卓越：双符号值独立分解（Dual-SVID）确保了量化感知训练（QAT）初始化的稳定性，而集成的残差补偿机制则有效缓解了误差问题。大量实验结果证实了LittleBit在低于1比特量化领域的优势：例如，其在Llama2-7B上的0.1BPW表现超越了现有领先方法的0.7BPW水平。这一成果确立了卓越的规模-性能权衡，内核级别基准测试显示，与FP16相比，其速度有望提升5倍。LittleBit为在资源受限环境中部署强大的LLMs铺平了道路。

> Deploying large language models (LLMs) often faces challenges from substantial memory and computational costs. Quantization offers a solution, yet performance degradation in the sub-1-bit regime remains particularly difficult. This paper introduces LittleBit, a novel method for extreme LLM compression. It targets levels like 0.1 bits per weight (BPW), achieving nearly 31$\times$ memory reduction, e.g., Llama2-13B to under 0.9 GB. LittleBit represents weights in a low-rank form using latent matrix factorization, subsequently binarizing these factors. To counteract information loss from this extreme precision, it integrates a multi-scale compensation mechanism. This includes row, column, and an additional latent dimension that learns per-rank importance. Two key contributions enable effective training: Dual Sign-Value-Independent Decomposition (Dual-SVID) for stable quantization-aware training (QAT) initialization, and integrated Residual Compensation to mitigate errors. Extensive experiments confirm LittleBit's superiority in sub-1-bit quantization: e.g., its 0.1 BPW performance on Llama2-7B surpasses the leading method's 0.7 BPW. This establishes a superior size-performance trade-off, with kernel-level benchmarks indicating potential for a 5$\times$ speedup compared to FP16. LittleBit paves the way for deploying powerful LLMs in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2506.13771)