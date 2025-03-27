# MATHGLANCE：多模态大型语言模型在数学图中迷失方向

发布时间：2025年03月26日

`LLM应用` `计算机视觉`

> MATHGLANCE: Multimodal Large Language Models Do Not Know Where to Look in Mathematical Diagrams

# 摘要

> 图表作为视觉语言的基础形式，通过符号、形状和空间布局表达复杂概念及其关系。与自然图像不同，其本质上符号化和抽象化的特性为多模态大型语言模型（MLLMs）带来了独特挑战。现有基准测试将感知与推理任务混为一谈，难以评估MLLMs是否真正理解数学图表，而非简单模式识别。为解决这一问题，我们推出MATHGLANCE，一个专为评估MLLMs数学感知能力设计的基准测试。MATHGLANCE包含1.2K图像和1.6K精心策划的问题，涵盖形状分类、物体计数、关系识别和物体定位四项任务，涉及平面几何、立体几何和图形表示等多个领域。我们的评估显示，MLLMs在理解图表方面的能力明显受限，尤其在细粒度定位任务中表现不足。为应对这一挑战，我们构建了GeoPeP，一个包含20万结构化几何图像-文本对的感知导向数据集，其中明确标注了几何基本元素和精确的空间关系。在GeoPeP上训练MLLMs显著提升了其感知准确性，进而大幅增强了数学推理能力。我们的基准测试和数据集为评估和提升多模态数学理解设定了关键标准，为未来MLLM研究提供了宝贵资源和见解。

> Diagrams serve as a fundamental form of visual language, representing complex concepts and their inter-relationships through structured symbols, shapes, and spatial arrangements. Unlike natural images, their inherently symbolic and abstract nature poses significant challenges for Multimodal Large Language Models (MLLMs). However, current benchmarks conflate perceptual and reasoning tasks, making it difficult to assess whether MLLMs genuinely understand mathematical diagrams beyond superficial pattern recognition. To address this gap, we introduce MATHGLANCE, a benchmark specifically designed to isolate and evaluate mathematical perception in MLLMs. MATHGLANCE comprises 1.2K images and 1.6K carefully curated questions spanning four perception tasks: shape classification, object counting, relationship identification, and object grounding, covering diverse domains including plane geometry, solid geometry, and graphical representations. Our evaluation of MLLMs reveals that their ability to understand diagrams is notably limited, particularly in fine-grained grounding tasks. In response, we construct GeoPeP, a perception-oriented dataset of 200K structured geometry image-text pairs explicitly annotated with geometric primitives and precise spatial relationships. Training MLLM on GeoPeP leads to significant gains in perceptual accuracy, which in turn substantially improves mathematical reasoning. Our benchmark and dataset establish critical standards for evaluating and advancing multimodal mathematical understanding, providing valuable resources and insights to foster future MLLM research.

[Arxiv](https://arxiv.org/abs/2503.20745)