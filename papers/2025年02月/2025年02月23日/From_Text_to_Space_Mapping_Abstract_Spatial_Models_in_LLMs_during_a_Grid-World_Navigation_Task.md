# 从文本到空间：探索LLMs中的抽象空间模型及其在网格世界导航任务中的映射

发布时间：2025年02月23日

`LLM应用

分类说明：这篇论文探讨了大型语言模型（LLMs）如何处理空间信息，并将其应用于智能体导航任务。研究分析了不同空间表示对模型性能的影响，并深入探讨了模型内部机制。这些内容属于LLM在特定任务中的应用和性能分析，因此归类为LLM应用。` `人工智能` `机器人技术`

> From Text to Space: Mapping Abstract Spatial Models in LLMs during a Grid-World Navigation Task

# 摘要

> 理解大型语言模型（LLMs）如何处理空间信息，对于构建能够应对真实与虚拟环境的智能体系统至关重要。本研究聚焦于不同文本形式的空间表示对LLM在网格世界导航任务中表现及内部机制的影响。通过对不同规模模型在目标导向导航任务中的评估，我们揭示了空间信息编码格式对决策过程的关键影响。实验结果表明，采用笛卡尔空间表示始终能取得更高的成功率和路径效率，且性能随模型规模显著提升。此外，对LLaMA-3.1-8B的深入分析发现，其内部单元中存在与空间特征（如智能体位置或动作正确性）高度相关且稳定的子集，这些单元主要分布在中间层，无论空间信息如何表示，并且也能被无关的空间推理任务激活。这项研究不仅深化了我们对LLMs处理空间信息的理解，更为开发更具解释性和健壮性的智能体AI系统提供了重要启示。


> Understanding how large language models (LLMs) represent and reason about spatial information is crucial for building robust agentic systems that can navigate real and simulated environments. In this work, we investigate the influence of different text-based spatial representations on LLM performance and internal activations in a grid-world navigation task. By evaluating models of various sizes on a task that requires navigating toward a goal, we examine how the format used to encode spatial information impacts decision-making. Our experiments reveal that cartesian representations of space consistently yield higher success rates and path efficiency, with performance scaling markedly with model size. Moreover, probing LLaMA-3.1-8B revealed subsets of internal units, primarily located in intermediate layers, that robustly correlate with spatial features, such as the position of the agent in the grid or action correctness, regardless of how that information is represented, and are also activated by unrelated spatial reasoning tasks. This work advances our understanding of how LLMs process spatial information and provides valuable insights for developing more interpretable and robust agentic AI systems.

[Arxiv](https://arxiv.org/abs/2502.16690)