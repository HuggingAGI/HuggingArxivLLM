# 超越模式识别：探秘语言模型的内部表征

发布时间：2025年02月23日

`LLM理论` `人工智能`

> Beyond Pattern Recognition: Probing Mental Representations of LMs

# 摘要

> 语言模型（LMs）在解决复杂推理任务方面表现出色，尤其是在生成中间解释时。然而，这些中间推理过程究竟是动态变化的思维过程，还是仅反映模式识别能力，尚不明确。受人类认知启发，推理随新信息整合和内部模型更新逐步展开，我们深入研究了语言模型的内部思维模型。我们提出了一种新的评估方法，逐步提供问题细节，使每个新信息都能优化模型的内部表示。我们系统比较了这种逐步建模策略与传统全提示方法在纯文本和图文模态下的表现。实验显示，无论模型规模和问题复杂度如何，文本和多模态模型都难以构建内部表示，这引发了对它们内部认知过程的质疑。

> Language Models (LMs) have demonstrated impressive capabilities in solving complex reasoning tasks, particularly when prompted to generate intermediate explanations. However, it remains an open question whether these intermediate reasoning traces represent a dynamic, evolving thought process or merely reflect sophisticated pattern recognition acquired during large scale pre training. Drawing inspiration from human cognition, where reasoning unfolds incrementally as new information is assimilated and internal models are continuously updated, we propose to delve deeper into the mental model of various LMs. We propose a new way to assess the mental modeling of LMs, where they are provided with problem details gradually, allowing each new piece of data to build upon and refine the model's internal representation of the task. We systematically compare this step by step mental modeling strategy with traditional full prompt methods across both text only and vision and text modalities. Experiments on the MathWorld dataset across different model sizes and problem complexities confirm that both text-based LLMs and multimodal LMs struggle to create mental representations, questioning how their internal cognitive processes work.

[Arxiv](https://arxiv.org/abs/2502.16717)