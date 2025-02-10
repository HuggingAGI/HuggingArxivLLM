# 基于位置的自动电路探索

发布时间：2025年02月06日

`LLM理论` `人工智能`

> Position-aware Automatic Circuit Discovery

# 摘要

> 电路分析是一种广泛用于揭示语言模型内部机制的策略。电路是模型计算图中执行特定任务的最小子图。我们发现现有电路发现方法存在一个显著不足：它们假设电路是位置不变的，认为模型组件在不同输入位置的相关性相同。这极大限制了它们捕捉跨位置交互或在不同位置变化的机制的能力。为了解决这一问题，我们提出两项创新改进，将位置性引入电路分析，即使在包含变长示例的任务中也是如此。

首先，我们扩展了基于梯度的电路发现方法——边归因修补，使其能够区分不同标记位置。其次，我们引入了数据集模式的概念，该模式定义了具有相似语义的标记跨度，使在变长示例数据集中发现位置感知电路成为可能。我们还开发了一个使用大型语言模型实现模式生成和应用的自动化管道。通过这些创新，我们的方法实现了完全自动化的发现位置敏感电路，与先前工作相比，在电路规模和保真度之间取得了更好的权衡，为理解语言模型的内部机制提供了新的视角。

> A widely used strategy to discover and understand language model mechanisms is circuit analysis. A circuit is a minimal subgraph of a model's computation graph that executes a specific task. We identify a gap in existing circuit discovery methods: they assume circuits are position-invariant, treating model components as equally relevant across input positions. This limits their ability to capture cross-positional interactions or mechanisms that vary across positions. To address this gap, we propose two improvements to incorporate positionality into circuits, even on tasks containing variable-length examples. First, we extend edge attribution patching, a gradient-based method for circuit discovery, to differentiate between token positions. Second, we introduce the concept of a dataset schema, which defines token spans with similar semantics across examples, enabling position-aware circuit discovery in datasets with variable length examples. We additionally develop an automated pipeline for schema generation and application using large language models. Our approach enables fully automated discovery of position-sensitive circuits, yielding better trade-offs between circuit size and faithfulness compared to prior work.

[Arxiv](https://arxiv.org/abs/2502.04577)