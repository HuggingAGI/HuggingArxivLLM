# 使用稀疏自动编码器分析视觉模型中的层级结构

发布时间：2025年05月21日

`其他` `计算机视觉`

> Analyzing Hierarchical Structure in Vision Models with Sparse Autoencoders

# 摘要

> ImageNet层次结构为分析深度视觉模型的表示学习提供了一个结构化的分类视角。本研究通过稀疏自动编码器（SAEs）全面探究视觉模型如何编码ImageNet层次结构。SAEs作为大型语言模型（LLMs）的解释工具已被广泛应用，能够揭示语义特征。我们将其扩展到视觉模型领域，研究学习到的表示是否与ImageNet的本体结构一致。研究发现，SAEs揭示了模型激活中的层次关系，表明模型对分类结构的隐式编码能力。我们分析了视觉基础模型DINOv2不同层中表示的一致性，揭示了深度视觉模型通过增加类标记信息来内化层次类别信息的机制。本研究构建了一个系统分析视觉模型表示层次结构的框架，并展示了SAEs在探测深度网络语义结构方面的潜力。

> The ImageNet hierarchy provides a structured taxonomy of object categories, offering a valuable lens through which to analyze the representations learned by deep vision models. In this work, we conduct a comprehensive analysis of how vision models encode the ImageNet hierarchy, leveraging Sparse Autoencoders (SAEs) to probe their internal representations. SAEs have been widely used as an explanation tool for large language models (LLMs), where they enable the discovery of semantically meaningful features. Here, we extend their use to vision models to investigate whether learned representations align with the ontological structure defined by the ImageNet taxonomy. Our results show that SAEs uncover hierarchical relationships in model activations, revealing an implicit encoding of taxonomic structure. We analyze the consistency of these representations across different layers of the popular vision foundation model DINOv2 and provide insights into how deep vision models internalize hierarchical category information by increasing information in the class token through each layer. Our study establishes a framework for systematic hierarchical analysis of vision model representations and highlights the potential of SAEs as a tool for probing semantic structure in deep networks.

[Arxiv](https://arxiv.org/abs/2505.15970)