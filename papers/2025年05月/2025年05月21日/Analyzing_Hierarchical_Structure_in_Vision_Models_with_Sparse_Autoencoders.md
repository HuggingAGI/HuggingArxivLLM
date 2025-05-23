# # 分析视觉模型中的层次结构：使用稀疏自编码器
研究视觉模型中的层次结构特征，采用稀疏自编码器进行分析。

发布时间：2025年05月21日

`其他

理由：这篇论文探讨了视觉模型（如DINOv2）如何编码ImageNet层次结构，并使用稀疏自动编码器（SAEs）来分析模型的内部表示。虽然提到了大型语言模型（LLMs）的应用，但研究的重点在于视觉模型和其表示结构，而不是直接讨论LLM的应用或理论。因此，它更适合归类为“其他”。` `计算机视觉`

> Analyzing Hierarchical Structure in Vision Models with Sparse Autoencoders

# 摘要

> ImageNet层次结构为分析深度视觉模型的学习表示提供了一个结构化的分类框架。在本研究中，我们全面分析了视觉模型如何编码ImageNet层次结构，利用稀疏自动编码器（SAEs）探查其内部表示。SAEs作为大型语言模型（LLMs）的解释工具已广泛应用，能够揭示语义有意义的特征。在此，我们将SAEs的应用扩展到视觉模型，研究学习到的表示是否与ImageNet分类法定义的本体结构一致。我们的结果显示，SAEs揭示了模型激活中的层次关系，表明对分类结构的隐式编码。我们分析了流行视觉基础模型DINOv2不同层中这些表示的一致性，并探讨了深度视觉模型如何通过每层增加类标记中的信息来内部化层次类别信息。本研究为系统分析视觉模型表示的层次结构提供了框架，并突显了SAEs作为探查深度网络语义结构工具的潜力。

> The ImageNet hierarchy provides a structured taxonomy of object categories, offering a valuable lens through which to analyze the representations learned by deep vision models. In this work, we conduct a comprehensive analysis of how vision models encode the ImageNet hierarchy, leveraging Sparse Autoencoders (SAEs) to probe their internal representations. SAEs have been widely used as an explanation tool for large language models (LLMs), where they enable the discovery of semantically meaningful features. Here, we extend their use to vision models to investigate whether learned representations align with the ontological structure defined by the ImageNet taxonomy. Our results show that SAEs uncover hierarchical relationships in model activations, revealing an implicit encoding of taxonomic structure. We analyze the consistency of these representations across different layers of the popular vision foundation model DINOv2 and provide insights into how deep vision models internalize hierarchical category information by increasing information in the class token through each layer. Our study establishes a framework for systematic hierarchical analysis of vision model representations and highlights the potential of SAEs as a tool for probing semantic structure in deep networks.

[Arxiv](https://arxiv.org/abs/2505.15970)