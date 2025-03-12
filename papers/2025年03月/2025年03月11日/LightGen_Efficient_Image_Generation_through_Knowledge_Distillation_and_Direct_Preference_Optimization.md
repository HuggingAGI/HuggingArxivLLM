# LightGen：高效图像生成，知识蒸馏与直接偏好优化齐上阵

发布时间：2025年03月11日

`其他` `人工智能` `图像生成`

> LightGen: Efficient Image Generation through Knowledge Distillation and Direct Preference Optimization

# 摘要

> 近年来，文本到图像生成领域的突破主要依赖于大规模数据集和参数密集型架构，这使得资源有限的研究者和从业者难以参与。本文提出了一种名为LightGen的高效图像生成模型训练范式，结合了知识蒸馏（KD）和直接偏好优化（DPO）。借鉴多模态大型语言模型（MLLMs）中数据蒸馏技术的成功经验，LightGen将最先进的（SOTA）文本到图像模型的知识蒸馏到一个仅有$0.7B$参数的紧凑掩码自回归（MAR）架构中。通过使用一个仅包含$2M$张高质量图像的紧凑合成数据集（由多样化描述生成），我们发现数据多样性在决定模型性能方面远比数据量更重要。这一策略大幅降低了计算需求，将预训练时间从潜在的数千GPU天缩短至仅88GPU天。此外，为了解决合成数据的固有缺陷，特别是高频细节缺失和空间不准确的问题，我们集成了DPO技术，以提升图像保真度和位置精度。全面的实验表明，LightGen在生成图像质量上可与SOTA模型相媲美，同时显著降低了计算资源需求，并为资源受限的环境扩大了可及性。代码可在https://github.com/XianfengWu01/LightGen获取

> Recent advances in text-to-image generation have primarily relied on extensive datasets and parameter-heavy architectures. These requirements severely limit accessibility for researchers and practitioners who lack substantial computational resources. In this paper, we introduce \model, an efficient training paradigm for image generation models that uses knowledge distillation (KD) and Direct Preference Optimization (DPO). Drawing inspiration from the success of data KD techniques widely adopted in Multi-Modal Large Language Models (MLLMs), LightGen distills knowledge from state-of-the-art (SOTA) text-to-image models into a compact Masked Autoregressive (MAR) architecture with only $0.7B$ parameters. Using a compact synthetic dataset of just $2M$ high-quality images generated from varied captions, we demonstrate that data diversity significantly outweighs data volume in determining model performance. This strategy dramatically reduces computational demands and reduces pre-training time from potentially thousands of GPU-days to merely 88 GPU-days. Furthermore, to address the inherent shortcomings of synthetic data, particularly poor high-frequency details and spatial inaccuracies, we integrate the DPO technique that refines image fidelity and positional accuracy. Comprehensive experiments confirm that LightGen achieves image generation quality comparable to SOTA models while significantly reducing computational resources and expanding accessibility for resource-constrained environments. Code is available at https://github.com/XianfengWu01/LightGen

[Arxiv](https://arxiv.org/abs/2503.08619)