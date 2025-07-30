# # ChartM$^3$: 基于多模态指令的图表编辑基准评测

发布时间：2025年07月25日

`LLM应用` `数据分析` `数据可视化`

> ChartM$^3$: Benchmarking Chart Editing with Multimodal Instructions

# 摘要

> 图表是数据可视化的基本形式，在科研和工业领域的数据分析中被广泛应用。尽管基于高层次意图编辑图表具有很大的实用价值，但现有方法主要依赖自然语言指令，这些指令通常过于模糊，无法支持精细的编辑操作。在本研究中，我们引入了一种全新的多模态图表编辑范式，其中用户意图通过自然语言和视觉指示符的结合来表达，后者能够明确突出需要修改的元素。为了支持这一范式，我们提出了Chart$	ext{M}^3$，这是一个全新的多模态图表编辑基准，具有多层级复杂度和多角度评估能力。Chart$	ext{M}^3$包含了1,000个样本，涵盖了四个难度级别。每个样本包括以（图表，代码，多模态指令）形式存在的三元组。为了全面评估图表编辑模型，Chart$	ext{M}^3$提供了评估视觉外观和代码正确性的指标。我们的基准测试揭示了当前多模态大型语言模型（MLLMs）如GPT-4o的重大限制，特别是在解读和处理视觉指示符方面。为此，我们构建了Chart$	ext{M}^3$-Train，这是一个包含24,000个多模态图表编辑样本的大型训练集。在该数据集上对MLLMs进行微调显著提升了性能，证明了多模态监督在构建实用图表编辑系统中的重要性。我们的数据集、代码和评估工具可在https://github.com/MLrollIT/ChartM3获取。%https://github.com/MLrollIT/ChartM3我们的数据集、代码和评估工具可在https://github.com/yaolinli/VCE获取。

> Charts are a fundamental visualization format widely used in data analysis across research and industry. While enabling users to edit charts based on high-level intentions is of great practical value, existing methods primarily rely on natural language instructions, which are often too ambiguous to support fine-grained editing. In this work, we introduce a novel paradigm for multimodal chart editing, where user intent is expressed through a combination of natural language and visual indicators that explicitly highlight the elements to be modified. To support this paradigm, we present Chart$\text{M}^3$, a new benchmark for Multimodal chart editing with Multi-level complexity and Multi-perspective evaluation. Chart$\text{M}^3$ contains 1,000 samples spanning four levels of editing difficulty. Each sample includes triplets in the form of (chart, code, multimodal instructions). To comprehensively evaluate chart editing models, Chart$\text{M}^3$ provides metrics that assess both visual appearance and code correctness. Our benchmark reveals significant limitations in current multimodal large language models (MLLMs), including GPT-4o, particularly in their ability to interpret and act on visual indicators. To address this, we construct Chart$\text{M}^3$-Train, a large-scale training set with 24,000 multimodal chart editing samples. Fine-tuning MLLMs on this dataset leads to substantial improvements, demonstrating the importance of multimodal supervision in building practical chart editing systems. Our datasets, codes, and evaluation tools are available at https://github.com/MLrollIT/ChartM3. %https://github.com/MLrollIT/ChartM3Our datasets, codes, and evaluation tools are available at https://github.com/yaolinli/VCE.

[Arxiv](https://arxiv.org/abs/2507.21167)