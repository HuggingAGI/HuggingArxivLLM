# 探索Transformer内部世界：InTraVisTo可视化工具

发布时间：2025年07月18日

`LLM应用` `大型语言模型` `模型分析`

> InTraVisTo: Inside Transformer Visualisation Tool

# 摘要

> 大型语言模型（LLMs）的推理能力在过去几年中显著提升，同时其规模和复杂性也大幅增加。然而，由于其不可预测的特性和期望行为与实际模型输出之间的潜在差异，将LLMs应用于生产环境仍然面临诸多挑战。本文中，我们介绍了一款新工具——InTraVisTo（Inside Transformer Visualisation Tool），旨在帮助研究人员探究并追踪基于Transformer的LLM生成每个token的计算过程。InTraVisTo能够通过解码模型各层中的token嵌入，展示Transformer模型的内部状态；同时，它还利用桑基图（Sankey diagram）展示模型不同层之间各组件间的信息流动。借助InTraVisTo，我们希望助力研究人员和从业者更好地理解Transformer模型内部执行的计算过程，从而揭示LLMs所采用的内部模式和推理机制。

> The reasoning capabilities of Large Language Models (LLMs) have increased greatly over the last few years, as have their size and complexity. Nonetheless, the use of LLMs in production remains challenging due to their unpredictable nature and discrepancies that can exist between their desired behavior and their actual model output. In this paper, we introduce a new tool, InTraVisTo (Inside Transformer Visualisation Tool), designed to enable researchers to investigate and trace the computational process that generates each token in a Transformer-based LLM. InTraVisTo provides a visualization of both the internal state of the Transformer model (by decoding token embeddings at each layer of the model) and the information flow between the various components across the different layers of the model (using a Sankey diagram). With InTraVisTo, we aim to help researchers and practitioners better understand the computations being performed within the Transformer model and thus to shed some light on internal patterns and reasoning processes employed by LLMs.

[Arxiv](https://arxiv.org/abs/2507.13858)