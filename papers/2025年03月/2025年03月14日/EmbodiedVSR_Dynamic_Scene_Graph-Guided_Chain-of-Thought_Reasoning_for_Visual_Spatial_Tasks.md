# EmbodiedVSR: 基于动态场景图的链式推理方法在视觉空间任务中的应用

发布时间：2025年03月14日

`LLM应用` `具身智能` `人工智能`

> EmbodiedVSR: Dynamic Scene Graph-Guided Chain-of-Thought Reasoning for Visual Spatial Tasks

# 摘要

> 多模态大型语言模型（MLLMs）在具身智能领域取得了革命性的进展，但在复杂长时任务中的空间推理能力仍有待突破。针对这一挑战，我们提出了一种创新性框架——EmbodiedVSR（具身视觉空间推理），通过动态场景图引导的思维链（CoT）推理，显著提升了具身智能体的空间理解能力。该框架利用动态场景图构建结构化知识表示，实现了无需任务微调的零样本空间推理，既能分解复杂的空间关系，又能使推理过程与环境动态完美结合。为了全面评估性能，我们推出了 eSpatial-Benchmark 数据集，包含真实具身场景、细致空间标注以及自适应难度的任务设置。实验结果表明，与现有 MLLM 方法相比，我们的框架在准确性和推理连贯性方面均实现了显著提升，尤其在需要迭代环境交互的长时任务中表现卓越。研究结果充分展现了配备结构化、可解释推理机制的 MLLMs 在具身智能领域的巨大潜力，为未来在现实世界空间应用中的可靠部署奠定了坚实基础。代码和数据集即将开放。

> While multimodal large language models (MLLMs) have made groundbreaking progress in embodied intelligence, they still face significant challenges in spatial reasoning for complex long-horizon tasks. To address this gap, we propose EmbodiedVSR (Embodied Visual Spatial Reasoning), a novel framework that integrates dynamic scene graph-guided Chain-of-Thought (CoT) reasoning to enhance spatial understanding for embodied agents. By explicitly constructing structured knowledge representations through dynamic scene graphs, our method enables zero-shot spatial reasoning without task-specific fine-tuning. This approach not only disentangles intricate spatial relationships but also aligns reasoning steps with actionable environmental dynamics. To rigorously evaluate performance, we introduce the eSpatial-Benchmark, a comprehensive dataset including real-world embodied scenarios with fine-grained spatial annotations and adaptive task difficulty levels. Experiments demonstrate that our framework significantly outperforms existing MLLM-based methods in accuracy and reasoning coherence, particularly in long-horizon tasks requiring iterative environment interaction. The results reveal the untapped potential of MLLMs for embodied intelligence when equipped with structured, explainable reasoning mechanisms, paving the way for more reliable deployment in real-world spatial applications. The codes and datasets will be released soon.

[Arxiv](https://arxiv.org/abs/2503.11089)