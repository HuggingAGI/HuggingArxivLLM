# 以思维作画：释放多模态推理的力量，生成科学图表

发布时间：2025年04月13日

`LLM应用

理由：这篇论文主要探讨了如何应用多模态大型语言模型（MLLMs）来解决科学图表的重构问题，属于LLM的应用层面。` `数据处理`

> Draw with Thought: Unleashing Multimodal Reasoning for Scientific Diagram Generation

# 摘要

> 科学图表是跨学科交流结构化知识的重要工具，但它们常以静态栅格图像形式发布，这不仅丢失了符号语义，还限制了再利用的可能性。虽然多模态大型语言模型（MLLMs）为连接视觉与结构提供了可能，但现有方法在语义控制和结构可解释性方面存在欠缺，尤其是在处理复杂图表时。我们提出了一种无需训练的框架——Draw with Thought（DwT），通过基于认知的链式推理（Chain-of-Thought）引导MLLMs将图表重构为可编辑的mxGraph XML代码。DwT通过将任务分为两个阶段，在无需模型微调的情况下实现了可解释且可控的输出：首先是粗到精规划阶段，处理感知结构化和语义规范；其次是结构感知代码生成阶段，借助格式引导的优化进行增强。为了支持评估，我们发布了Plot2XML，这是一个包含247个真实科学图表的数据集，附带黄金标准的XML标注。在八种MLLMs上的广泛实验表明，我们的方法能够生成高保真、语义对齐且结构有效的重构结果。人工评估证实了在准确性和视觉美学上的高度一致，为将静态视觉转化为可执行表示提供了一种可扩展的解决方案，同时推动了机器对科学图形的理解。

> Scientific diagrams are vital tools for communicating structured knowledge across disciplines. However, they are often published as static raster images, losing symbolic semantics and limiting reuse. While Multimodal Large Language Models (MLLMs) offer a pathway to bridging vision and structure, existing methods lack semantic control and structural interpretability, especially on complex diagrams. We propose Draw with Thought (DwT), a training-free framework that guides MLLMs to reconstruct diagrams into editable mxGraph XML code through cognitively-grounded Chain-of-Thought reasoning. DwT enables interpretable and controllable outputs without model fine-tuning by dividing the task into two stages: Coarse-to-Fine Planning, which handles perceptual structuring and semantic specification, and Structure-Aware Code Generation, enhanced by format-guided refinement. To support evaluation, we release Plot2XML, a benchmark of 247 real-world scientific diagrams with gold-standard XML annotations. Extensive experiments across eight MLLMs show that our approach yields high-fidelity, semantically aligned, and structurally valid reconstructions, with human evaluations confirming strong alignment in both accuracy and visual aesthetics, offering a scalable solution for converting static visuals into executable representations and advancing machine understanding of scientific graphics.

[Arxiv](https://arxiv.org/abs/2504.09479)