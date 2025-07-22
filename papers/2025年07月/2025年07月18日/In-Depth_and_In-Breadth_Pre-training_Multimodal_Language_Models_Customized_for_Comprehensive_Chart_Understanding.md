# 深入而全面：预训练定制的多模态语言模型实现图表的全面理解

发布时间：2025年07月18日

`LLM应用` `数据分析`

> In-Depth and In-Breadth: Pre-training Multimodal Language Models Customized for Comprehensive Chart Understanding

# 摘要

> 最近，针对特定领域任务定制大型视觉语言模型（LVLMs）的方法在科学图表理解领域取得了显著进展。然而，现有方法仍存在两大局限：其一，它们仅依赖有限几种图表类型的配对数据，导致在广泛图表类型上的泛化能力受限；其二，缺乏针对图表与数据对齐的专门预训练，影响了模型对底层数据的理解。本文提出ChartScope，一个专为深入理解多种图表类型而优化的LVLM。我们设计了一种高效的数据生成管道，能够合成适用于多种图表类型的配对数据，并提出了一种新型双路径训练策略，通过结合对底层数据的推理，使模型既能精准捕捉关键数据细节，又保持强大的推理能力。此外，我们还构建了ChartDQA，一个全新的基准测试，旨在全面评估问答能力和对底层数据的理解。实验结果表明，ChartScope在多种图表类型上的理解能力实现了显著提升。更多代码和数据可访问https://davidhalladay.github.io/chartscope_demo获取。

> Recent methods for customizing Large Vision Language Models (LVLMs) for domain-specific tasks have shown promising results in scientific chart comprehension. However, existing approaches face two major limitations: First, they rely on paired data from only a few chart types, limiting generalization to wide range of chart types. Secondly, they lack targeted pre-training for chart-data alignment, which hampers the model's understanding of underlying data. In this paper, we introduce ChartScope, an LVLM optimized for in-depth chart comprehension across diverse chart types. We propose an efficient data generation pipeline that synthesizes paired data for a wide range of chart types, along with a novel Dual-Path training strategy that enabling the model to succinctly capture essential data details while preserving robust reasoning capabilities by incorporating reasoning over the underlying data. Lastly, we establish ChartDQA, a new benchmark for evaluating not only question-answering at different levels but also underlying data understanding. Experimental results demonstrate that ChartScope significantly enhances comprehension on a wide range of chart types. The code and data are available at https://davidhalladay.github.io/chartscope_demo.

[Arxiv](https://arxiv.org/abs/2507.14298)