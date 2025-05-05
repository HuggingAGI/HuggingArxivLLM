# GLIP-OOD：基于基础模型的零样本图领域外检测

发布时间：2025年04月29日

`LLM应用` `图结构数据` `分布外检测`

> GLIP-OOD: Zero-Shot Graph OOD Detection with Foundation Model

# 摘要

> 分布外检测（OOD）是保障机器学习系统在动态开放环境下的安全与可靠性的关键。在视觉和文本领域，无需依赖在分布（ID）数据训练的零样本OOD检测，借助大规模预训练模型如视觉-语言模型（VLMs）和大型语言模型（LLMs）已取得显著进展。然而，针对图结构数据的零样本OOD检测仍处于探索初期，主要受限于复杂关系结构的挑战和缺乏强大图预训练模型。本研究首次通过图基础模型（GFM）实现零样本图OOD检测。实验表明，仅凭类别标签名称，GFM即可无需节点级监督完成OOD检测，并在多个数据集上超越现有监督方法。为应对实际场景中OOD标签不可用的挑战，我们提出GLIP-OOD框架，利用LLMs从无标签数据生成语义丰富的伪OOD标签。这些标签使GFM能够捕捉ID与OOD类间的细微语义边界，实现细粒度OOD检测——无需任何标签节点。本方法首次在完全零样本设置下实现节点级图OOD检测，并在四个基准文本属性图数据集上达到最优性能。


> Out-of-distribution (OOD) detection is critical for ensuring the safety and reliability of machine learning systems, particularly in dynamic and open-world environments. In the vision and text domains, zero-shot OOD detection - which requires no training on in-distribution (ID) data - has made significant progress through the use of large-scale pretrained models such as vision-language models (VLMs) and large language models (LLMs). However, zero-shot OOD detection in graph-structured data remains largely unexplored, primarily due to the challenges posed by complex relational structures and the absence of powerful, large-scale pretrained models for graphs. In this work, we take the first step toward enabling zero-shot graph OOD detection by leveraging a graph foundation model (GFM). We show that, when provided only with class label names, the GFM can perform OOD detection without any node-level supervision - outperforming existing supervised methods across multiple datasets. To address the more practical setting where OOD label names are unavailable, we introduce GLIP-OOD, a novel framework that employs LLMs to generate semantically informative pseudo-OOD labels from unlabeled data. These labels enable the GFM to capture nuanced semantic boundaries between ID and OOD classes and perform fine-grained OOD detection - without requiring any labeled nodes. Our approach is the first to enable node-level graph OOD detection in a fully zero-shot setting, and achieves state-of-the-art performance on four benchmark text-attributed graph datasets.

[Arxiv](https://arxiv.org/abs/2504.21186)