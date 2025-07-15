# # 合成邻近边界域外样本，助力域外检测

发布时间：2025年07月14日

`LLM应用` `计算机视觉` `生成对抗网络`

> Synthesizing Near-Boundary OOD Samples for Out-of-Distribution Detection

# 摘要

> 预训练的视觉语言模型展现出非凡的能力，能够检测出分布 (OOD) 样本。然而，某些接近在分布 (InD) 数据的具有挑战性的 OOD 样本仍可能导致误分类。幸运的是，扩散模型和多模态大型语言模型 (MLLMs) 等基础模型的出现为这一难题提供了一种创新的解决方案。我们提出了一种名为 SynOOD 的方法，通过利用基础模型生成合成的、具有挑战性的 OOD 数据，来微调 CLIP 模型，从而增强 InD 和 OOD 样本之间的边界级判别能力。我们的方法采用基于 MLLMs 的上下文提示引导的迭代修复过程，生成微妙且边界对齐的 OOD 样本。这些样本通过基于 OOD 评分（如能量评分）的梯度进行噪声调整，从而有效采样于 InD/OOD 边界。借助这些精心合成的图像，我们对 CLIP 图像编码器和源自文本编码器的负标签特征进行微调，从而加强近边界 OOD 样本与一组负标签之间的关联。最终，SynOOD 在大规模的 ImageNet 基准测试中达到了最先进的性能，仅需小幅增加参数和运行时间。我们的方法显著超越了现有方法，将 AUROC 提升了 2.80%，并将 FPR95 降低了 11.13%。代码可在 https://github.com/Jarvisgivemeasuit/SynOOD 获取。

> Pre-trained vision-language models have exhibited remarkable abilities in detecting out-of-distribution (OOD) samples. However, some challenging OOD samples, which lie close to in-distribution (InD) data in image feature space, can still lead to misclassification. The emergence of foundation models like diffusion models and multimodal large language models (MLLMs) offers a potential solution to this issue. In this work, we propose SynOOD, a novel approach that harnesses foundation models to generate synthetic, challenging OOD data for fine-tuning CLIP models, thereby enhancing boundary-level discrimination between InD and OOD samples. Our method uses an iterative in-painting process guided by contextual prompts from MLLMs to produce nuanced, boundary-aligned OOD samples. These samples are refined through noise adjustments based on gradients from OOD scores like the energy score, effectively sampling from the InD/OOD boundary. With these carefully synthesized images, we fine-tune the CLIP image encoder and negative label features derived from the text encoder to strengthen connections between near-boundary OOD samples and a set of negative labels. Finally, SynOOD achieves state-of-the-art performance on the large-scale ImageNet benchmark, with minimal increases in parameters and runtime. Our approach significantly surpasses existing methods, improving AUROC by 2.80% and reducing FPR95 by 11.13%. Codes are available in https://github.com/Jarvisgivemeasuit/SynOOD.

[Arxiv](https://arxiv.org/abs/2507.10225)