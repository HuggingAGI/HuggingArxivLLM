# 评测多模态大语言模型在化学表格的识别与理解任务中的表现

发布时间：2025年06月12日

`LLM应用` `多模态模型`

> Benchmarking Multimodal LLMs on Recognition and Understanding over Chemical Tables

# 摘要

> 化学表格通过符号表达、结构化变量和嵌入的分子图形编码了复杂的实验知识。然而，现有的基准测试大多忽略了这种多模态和领域特定的复杂性，限制了多模态大型语言模型在化学科学理解方面的支持能力。为此，我们提出了ChemTable——一个从文献实验部分整理的真实世界化学表格的大型基准。ChemTable包含专家标注的单元格多边形、逻辑布局和领域特定标签（如试剂、催化剂、产率和图形组件），并支持两大核心任务：（1）表格识别，涵盖结构解析和内容提取；（2）表格理解，包括基于表格结构和领域语义的描述性和推理性问答。我们在ChemTable上评估了多种多模态模型（包括开源和闭源模型），并获得了一系列具有实践和概念意义的发现。尽管模型在基本布局解析上表现尚可，但与人类相比，它们在描述性和推断性问答任务上仍存在显著局限性。此外，我们发现开源和闭源模型在多个维度上存在显著性能差距。这些结果不仅凸显了化学感知表格理解的挑战，也确立了ChemTable作为推进科学推理的严格且现实基准的地位。

> Chemical tables encode complex experimental knowledge through symbolic expressions, structured variables, and embedded molecular graphics. Existing benchmarks largely overlook this multimodal and domain-specific complexity, limiting the ability of multimodal large language models to support scientific understanding in chemistry. In this work, we introduce ChemTable, a large-scale benchmark of real-world chemical tables curated from the experimental sections of literature. ChemTable includes expert-annotated cell polygons, logical layouts, and domain-specific labels, including reagents, catalysts, yields, and graphical components and supports two core tasks: (1) Table Recognition, covering structure parsing and content extraction; and (2) Table Understanding, encompassing both descriptive and reasoning-oriented question answering grounded in table structure and domain semantics. We evaluated a range of representative multimodal models, including both open-source and closed-source models, on ChemTable and reported a series of findings with practical and conceptual insights. Although models show reasonable performance on basic layout parsing, they exhibit substantial limitations on both descriptive and inferential QA tasks compared to human performance, and we observe significant performance gaps between open-source and closed-source models across multiple dimensions. These results underscore the challenges of chemistry-aware table understanding and position ChemTable as a rigorous and realistic benchmark for advancing scientific reasoning.

[Arxiv](https://arxiv.org/abs/2506.11375)