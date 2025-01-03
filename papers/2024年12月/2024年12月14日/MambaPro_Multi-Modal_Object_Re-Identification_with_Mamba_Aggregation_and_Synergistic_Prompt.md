# MambaPro: 基于 Mamba 聚合与协同提示的多模态对象重识别

发布时间：2024年12月14日

`其他

理由：这篇论文主要讨论的是多模态物体重识别（ReID）任务，并提出了一种新的框架MambaPro来处理多模态数据。虽然论文中提到了CLIP等大规模预训练模型，但重点并不在于LLM（大型语言模型）的应用或理论，而是专注于多模态数据的处理和特征提取。因此，这篇论文更适合归类为“其他”，而不是与LLM直接相关的类别。` `计算机视觉` `物体识别`

> MambaPro: Multi-Modal Object Re-Identification with Mamba Aggregation and Synergistic Prompt

# 摘要

> # 摘要
多模态物体重识别（ReID）通过整合不同模态的互补图像信息来检索特定物体。近期，CLIP等大规模预训练模型在单模态ReID任务中表现亮眼，但在多模态ReID中的应用尚未探索。此外，现有多模态聚合方法在处理长序列时存在明显不足。为此，我们提出了MambaPro框架，专为多模态ReID设计。具体而言，我们首先使用并行前馈适配器（PFA）使CLIP适应多模态ReID，随后提出协同残差提示（SRP）来引导多模态特征的联合学习。最后，借助Mamba在长序列上的强大扩展能力，我们引入了Mamba聚合（MA）来高效建模模态间的交互。MambaPro能以更低复杂度提取更鲁棒的特征。在RGBNT201、RGBNT100和MSVR310三个基准上的实验验证了该方法的有效性。源代码已开源：https://github.com/924973292/MambaPro。

> Multi-modal object Re-IDentification (ReID) aims to retrieve specific objects by utilizing complementary image information from different modalities. Recently, large-scale pre-trained models like CLIP have demonstrated impressive performance in traditional single-modal object ReID tasks. However, they remain unexplored for multi-modal object ReID. Furthermore, current multi-modal aggregation methods have obvious limitations in dealing with long sequences from different modalities. To address above issues, we introduce a novel framework called MambaPro for multi-modal object ReID. To be specific, we first employ a Parallel Feed-Forward Adapter (PFA) for adapting CLIP to multi-modal object ReID. Then, we propose the Synergistic Residual Prompt (SRP) to guide the joint learning of multi-modal features. Finally, leveraging Mamba's superior scalability for long sequences, we introduce Mamba Aggregation (MA) to efficiently model interactions between different modalities. As a result, MambaPro could extract more robust features with lower complexity. Extensive experiments on three multi-modal object ReID benchmarks (i.e., RGBNT201, RGBNT100 and MSVR310) validate the effectiveness of our proposed methods. The source code is available at https://github.com/924973292/MambaPro.

[Arxiv](https://arxiv.org/abs/2412.10707)