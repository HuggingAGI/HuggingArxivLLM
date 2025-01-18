# 用于参考图像分割的密集连接参数高效调优

发布时间：2025年01月15日

`其他

理由：这篇论文主要讨论的是计算机视觉领域的参数高效调优（PET）方法，特别是针对未对齐编码器的多模态特征对齐问题。虽然论文中提到了文本适配器，但整体内容主要集中在计算机视觉领域的技术改进，而不是直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）相关的内容。因此，将其分类为“其他”更为合适。` `计算机视觉` `多模态学习`

> Densely Connected Parameter-Efficient Tuning for Referring Image Segmentation

# 摘要

> 在计算机视觉领域，参数高效调优（PET）正逐步取代传统的预训练后全微调模式。PET因其在大型基础模型中的卓越表现而备受推崇，不仅简化了迁移学习成本，还优化了硬件利用率。然而，当前的PET方法主要针对单模态优化设计。尽管已有一些开创性研究进行了初步探索，但它们仍局限于对齐编码器（如CLIP）的层面，尚未深入探索未对齐编码器。这些方法在未对齐编码器上表现欠佳，原因在于微调过程中无法有效对齐多模态特征。本文提出DETRIS，一个参数高效调优框架，通过在每个层与所有前层之间建立密集连接，增强低秩视觉特征传播，从而实现跨模态特征的有效交互，并适应未对齐编码器。我们还建议使用文本适配器来提升文本特征。这一简洁高效的方法在具有挑战性的基准测试中，仅更新0.9%到1.8%的主干参数，便大幅超越了现有最先进方法。项目地址：url{https://github.com/jiaqihuang01/DETRIS}。

> In the domain of computer vision, Parameter-Efficient Tuning (PET) is increasingly replacing the traditional paradigm of pre-training followed by full fine-tuning. PET is particularly favored for its effectiveness in large foundation models, as it streamlines transfer learning costs and optimizes hardware utilization. However, the current PET methods are mainly designed for single-modal optimization. While some pioneering studies have undertaken preliminary explorations, they still remain at the level of aligned encoders (e.g., CLIP) and lack exploration of misaligned encoders. These methods show sub-optimal performance with misaligned encoders, as they fail to effectively align the multimodal features during fine-tuning. In this paper, we introduce DETRIS, a parameter-efficient tuning framework designed to enhance low-rank visual feature propagation by establishing dense interconnections between each layer and all preceding layers, which enables effective cross-modal feature interaction and adaptation to misaligned encoders. We also suggest using text adapters to improve textual features. Our simple yet efficient approach greatly surpasses state-of-the-art methods with 0.9% to 1.8% backbone parameter updates, evaluated on challenging benchmarks. Our project is available at url{https://github.com/jiaqihuang01/DETRIS}.

[Arxiv](https://arxiv.org/abs/2501.08580)