# 空间推理中的想象：多模态思维可视化

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了如何通过多模态思维可视化（MVoT）来提升多模态大型语言模型（MLLMs）在复杂空间推理任务中的表现。虽然涉及到了思维链（CoT）提示和视觉思维的概念，但其核心在于应用这些方法来改进LLMs在实际任务中的表现，特别是复杂推理任务。因此，这篇论文应归类为LLM应用。` `人工智能` `多模态学习`

> Imagine while Reasoning in Space: Multimodal Visualization-of-Thought

# 摘要

> # 摘要
Chain-of-Thought (CoT) 提示在提升 LLMs 和 MLLMs 的复杂推理能力方面表现出色，但在复杂空间推理任务中却力不从心。然而，人类的认知不仅限于语言，还能在文字与图像之间自由切换。受此启发，我们提出了多模态思维可视化（MVoT）这一新范式，通过在 MLLMs 中生成推理轨迹的图像来实现视觉思维。为了确保高质量的可视化效果，我们在自回归 MLLMs 中引入了 token 差异损失，显著提升了视觉连贯性和保真度。通过多个动态空间推理任务的验证，实验结果显示 MVoT 在各项任务中表现优异，尤其在 CoT 难以应对的复杂场景中，MVoT 展现出了强大的改进能力。最终，MVoT 为复杂推理任务开辟了新路径，视觉思维与语言推理的互补为未来研究提供了更多可能性。

> Chain-of-Thought (CoT) prompting has proven highly effective for enhancing complex reasoning in Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs). Yet, it struggles in complex spatial reasoning tasks. Nonetheless, human cognition extends beyond language alone, enabling the remarkable capability to think in both words and images. Inspired by this mechanism, we propose a new reasoning paradigm, Multimodal Visualization-of-Thought (MVoT). It enables visual thinking in MLLMs by generating image visualizations of their reasoning traces. To ensure high-quality visualization, we introduce token discrepancy loss into autoregressive MLLMs. This innovation significantly improves both visual coherence and fidelity. We validate this approach through several dynamic spatial reasoning tasks. Experimental results reveal that MVoT demonstrates competitive performance across tasks. Moreover, it exhibits robust and reliable improvements in the most challenging scenarios where CoT fails. Ultimately, MVoT establishes new possibilities for complex reasoning tasks where visual thinking can effectively complement verbal reasoning.

[Arxiv](https://arxiv.org/abs/2501.07542)