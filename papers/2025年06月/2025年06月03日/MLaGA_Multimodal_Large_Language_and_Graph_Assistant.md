# MLaGA：多模态大型语言与图助理

发布时间：2025年06月03日

`LLM应用` `图结构数据分析` `多模态数据处理`

> MLaGA: Multimodal Large Language and Graph Assistant

# 摘要

> 大型语言模型（LLMs）在图结构数据分析领域展现了强大的能力。现有的基于LLM的图方法在处理文本丰富的图（即节点属性为文本描述的图）方面表现优异。然而，尽管多模态图（节点属性包含文本、图像等多种类型）在现实场景中普遍存在，但LLMs在这一领域的应用研究仍显不足。为填补这一空白，我们提出了一种创新模型——多模态大型语言和图助手（MLaGA），旨在将LLM的能力扩展到支持对复杂图结构和多模态属性的推理。首先，我们设计了一个结构感知的多模态编码器，通过联合图预训练目标将文本和视觉属性对齐到统一空间。接着，我们采用多模态指令微调方法，借助轻量级投影器将多模态特征和图结构无缝融入LLM。在多个数据集上的实验结果表明，MLaGA相较于现有领先方法，在监督学习和迁移学习场景下的各类图学习任务中均展现出更为卓越的性能。

> Large Language Models (LLMs) have demonstrated substantial efficacy in advancing graph-structured data analysis. Prevailing LLM-based graph methods excel in adapting LLMs to text-rich graphs, wherein node attributes are text descriptions. However, their applications to multimodal graphs--where nodes are associated with diverse attribute types, such as texts and images--remain underexplored, despite their ubiquity in real-world scenarios. To bridge the gap, we introduce the Multimodal Large Language and Graph Assistant (MLaGA), an innovative model that adeptly extends LLM capabilities to facilitate reasoning over complex graph structures and multimodal attributes. We first design a structure-aware multimodal encoder to align textual and visual attributes within a unified space through a joint graph pre-training objective. Subsequently, we implement a multimodal instruction-tuning approach to seamlessly integrate multimodal features and graph structures into the LLM through lightweight projectors. Extensive experiments across multiple datasets demonstrate the effectiveness of MLaGA compared to leading baseline methods, achieving superior performance in diverse graph learning tasks under both supervised and transfer learning scenarios.

[Arxiv](https://arxiv.org/abs/2506.02568)