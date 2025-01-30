# 利用FP4量化优化大型语言模型训练

发布时间：2025年01月28日

`LLM理论

**理由**：这篇论文主要讨论了如何通过量化训练（如FP4）来降低大型语言模型（LLMs）训练的计算成本，并提出了新的训练框架和技术创新。这些内容属于对LLM训练方法的理论研究和优化，因此应归类为LLM理论。` `人工智能` `硬件加速`

> Optimizing Large Language Model Training Using FP4 Quantization

# 摘要

> 随着训练大型语言模型（LLMs）的计算需求不断攀升，寻找更高效的方法变得至关重要。量化训练通过低比特运算降低成本，展现出巨大潜力。尽管FP8精度已证明可行，但FP4的应用仍面临量化误差大和表示能力有限的挑战。为此，我们推出了首个LLMs的FP4训练框架，通过两项创新突破：一是可微分量化估计器，确保权重更新的精确性；二是异常值钳位与补偿策略，防止激活崩溃。为确保稳定性，框架还融合了混合精度训练和向量级量化。实验显示，FP4框架在准确性上与BF16和FP8相当，性能损失极小，并能有效扩展至100B token训练的13B参数LLMs。随着支持FP4的新一代硬件问世，我们的框架为超低精度训练奠定了坚实基础。

> The growing computational demands of training large language models (LLMs) necessitate more efficient methods. Quantized training presents a promising solution by enabling low-bit arithmetic operations to reduce these costs. While FP8 precision has demonstrated feasibility, leveraging FP4 remains a challenge due to significant quantization errors and limited representational capacity. This work introduces the first FP4 training framework for LLMs, addressing these challenges with two key innovations: a differentiable quantization estimator for precise weight updates and an outlier clamping and compensation strategy to prevent activation collapse. To ensure stability, the framework integrates a mixed-precision training scheme and vector-wise quantization. Experimental results demonstrate that our FP4 framework achieves accuracy comparable to BF16 and FP8, with minimal degradation, scaling effectively to 13B-parameter LLMs trained on up to 100B tokens. With the emergence of next-generation hardware supporting FP4, our framework sets a foundation for efficient ultra-low precision training.

[Arxiv](https://arxiv.org/abs/2501.17116)