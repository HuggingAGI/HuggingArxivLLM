# IDEA：基于逆向文本与协同可变形聚合的多模态目标重识别方法

发布时间：2025年03月13日

`LLM应用` `智能交通`

> IDEA: Inverted Text with Cooperative Deformable Aggregation for Multi-modal Object Re-Identification

# 摘要

> 多模态目标重识别（ReID）的目标是通过多种模态的互补信息来检索特定目标。然而，现有方法主要关注异构视觉特征的融合，忽视了基于文本语义信息的潜力。为解决这一问题，我们构建了三个基于文本增强的多模态目标ReID基准数据集。具体来说，我们提出了一种基于多模态大型语言模型（MLLMs）的标准化多模态描述生成管道，用于生成结构化且简洁的文本标注。此外，现有方法通常直接聚合多模态信息，而没有选择具有代表性的局部特征，导致冗余和复杂度问题。为了解决这些问题，我们提出了IDEA框架，包含反向多模态特征提取器（IMFE）和协同可变形聚合（CDA）。IMFE通过模态前缀和InverseNet，在反转文本的语义指导下整合多模态信息。CDA自适应生成采样位置，使模型能够关注全局特征与判别性局部特征的交互。借助构建的基准数据集和提出的模块，我们的框架可以在复杂场景下生成更强大的多模态特征。在三个多模态目标ReID基准数据集上的大量实验验证了我们方法的有效性。


> Multi-modal object Re-IDentification (ReID) aims to retrieve specific objects by utilizing complementary information from various modalities. However, existing methods focus on fusing heterogeneous visual features, neglecting the potential benefits of text-based semantic information. To address this issue, we first construct three text-enhanced multi-modal object ReID benchmarks. To be specific, we propose a standardized multi-modal caption generation pipeline for structured and concise text annotations with Multi-modal Large Language Models (MLLMs). Besides, current methods often directly aggregate multi-modal information without selecting representative local features, leading to redundancy and high complexity. To address the above issues, we introduce IDEA, a novel feature learning framework comprising the Inverted Multi-modal Feature Extractor (IMFE) and Cooperative Deformable Aggregation (CDA). The IMFE utilizes Modal Prefixes and an InverseNet to integrate multi-modal information with semantic guidance from inverted text. The CDA adaptively generates sampling positions, enabling the model to focus on the interplay between global features and discriminative local features. With the constructed benchmarks and the proposed modules, our framework can generate more robust multi-modal features under complex scenarios. Extensive experiments on three multi-modal object ReID benchmarks demonstrate the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2503.10324)