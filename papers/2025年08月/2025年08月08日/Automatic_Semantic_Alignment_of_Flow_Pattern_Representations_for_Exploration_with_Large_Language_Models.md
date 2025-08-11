# 基于大型语言模型的自动语义对齐流程模式表示探索

发布时间：2025年08月08日

`LLM应用

理由：这篇论文探讨了将大型语言模型应用于流数据的交互式分析和可视化，属于LLM的应用层面。` `数据可视化` `科学计算`

> Automatic Semantic Alignment of Flow Pattern Representations for Exploration with Large Language Models

# 摘要

> 探索性流可视化使领域专家能够通过交互式研究流模式来分析复杂的流结构。然而，传统的视觉界面通常依赖于专门的图形表示和交互方式，这需要额外的努力来学习和使用。自然语言交互提供了一种更直观的替代方案，但要教会机器识别各种科学概念并从流数据中提取相应的结构是一个巨大的挑战。在本文中，我们介绍了一个自动化的框架，它将流模式表示与大型语言模型（LLMs）的语义空间对齐，从而消除了手动标注的需要。我们的方法使用去噪自动编码器对流线段进行编码，并通过投影层将生成的流模式表示映射到LLM嵌入中。这种对齐通过注意力机制实现了文本嵌入与流表示之间的语义匹配，从而可以根据文本描述提取相应的流模式。为了提高可用性，我们开发了一个交互式界面，允许用户使用自然语言查询和可视化流结构。通过案例研究，我们展示了我们的框架在实现直观和智能的流探索方面的有效性。

> Explorative flow visualization allows domain experts to analyze complex flow structures by interactively investigating flow patterns. However, traditional visual interfaces often rely on specialized graphical representations and interactions, which require additional effort to learn and use. Natural language interaction offers a more intuitive alternative, but teaching machines to recognize diverse scientific concepts and extract corresponding structures from flow data poses a significant challenge. In this paper, we introduce an automated framework that aligns flow pattern representations with the semantic space of large language models (LLMs), eliminating the need for manual labeling. Our approach encodes streamline segments using a denoising autoencoder and maps the generated flow pattern representations to LLM embeddings via a projector layer. This alignment empowers semantic matching between textual embeddings and flow representations through an attention mechanism, enabling the extraction of corresponding flow patterns based on textual descriptions. To enhance accessibility, we develop an interactive interface that allows users to query and visualize flow structures using natural language. Through case studies, we demonstrate the effectiveness of our framework in enabling intuitive and intelligent flow exploration.

[Arxiv](https://arxiv.org/abs/2508.06300)