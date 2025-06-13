# # Graph-MLLM: 驾驭多模态大型语言模型，赋能多模态图学习

发布时间：2025年06月11日

`LLM应用` `社交网络` `推荐系统`

> Graph-MLLM: Harnessing Multimodal Large Language Models for Multimodal Graph Learning

# 摘要

> 多模态大型语言模型（MLLMs）在处理多种数据模态方面表现出卓越的能力。然而，现有方法往往只关注模态对齐，而忽略了数据点之间的结构关系。将多模态与结构化图信息结合（即多模态图，MMGs），对于社交网络、医疗和推荐系统等实际应用至关重要。现有的MMG学习方法根据对MLLMs的利用方式，主要分为三种范式：Encoder、Aligner和Predictor。MLLM-as-Encoder通过多模态特征融合增强图神经网络（GNNs）；MLLM-as-Aligner通过语言或隐藏空间对齐多模态属性，实现基于LLM的图推理；MLLM-as-Predictor则将MLLMs作为独立的推理器，通过上下文学习或微调进行预测。尽管这些方法有所进展，但MMG领域缺乏一个统一的基准来公平评估这些方法，使得目前的进展尚不明确。为了解决这一问题，我们提出了Graph-MLLM，这是一个全面的多模态图学习基准，通过系统地评估这三个范式在六个不同领域的数据集上进行测试。通过广泛的实验，我们发现同时考虑节点的视觉和文本属性有助于图学习，即使使用预训练的文本到图像对齐模型（如CLIP）作为编码器也是如此。我们还发现，将视觉属性转换为文本描述可以进一步提高性能，而不是直接使用视觉输入。此外，我们观察到，在特定的MMGs上对MLLMs进行微调，即使没有明确的图结构信息，也可以在大多数情况下实现最先进的结果。我们希望我们开源的库能够促进快速、公平的评估，并激发该领域进一步的创新研究。

> Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities in representing and understanding diverse modalities. However, they typically focus on modality alignment in a pairwise manner while overlooking structural relationships across data points. Integrating multimodality with structured graph information (i.e., multimodal graphs, MMGs) is essential for real-world applications such as social networks, healthcare, and recommendation systems. Existing MMG learning methods fall into three paradigms based on how they leverage MLLMs: Encoder, Aligner, and Predictor. MLLM-as-Encoder focuses on enhancing graph neural networks (GNNs) via multimodal feature fusion; MLLM-as-Aligner aligns multimodal attributes in language or hidden space to enable LLM-based graph reasoning; MLLM-as-Predictor treats MLLMs as standalone reasoners with in-context learning or fine-tuning. Despite their advances, the MMG field lacks a unified benchmark to fairly evaluate across these approaches, making it unclear what progress has been made. To bridge this gap, we present Graph-MLLM, a comprehensive benchmark for multimodal graph learning by systematically evaluating these three paradigms across six datasets with different domains. Through extensive experiments, we observe that jointly considering the visual and textual attributes of the nodes benefits graph learning, even when using pre-trained text-to-image alignment models (e.g., CLIP) as encoders. We also find that converting visual attributes into textual descriptions further improves performance compared to directly using visual inputs. Moreover, we observe that fine-tuning MLLMs on specific MMGs can achieve state-of-the-art results in most scenarios, even without explicit graph structure information. We hope that our open-sourced library will facilitate rapid, equitable evaluation and inspire further innovative research in this field.

[Arxiv](https://arxiv.org/abs/2506.10282)