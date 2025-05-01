# 无人机视觉语言导航：端到端解决方案

发布时间：2025年04月30日

`Agent` `无人机导航` `无人机`

> UAV-VLN: End-to-End Vision Language guided Navigation for UAVs

# 摘要

> 在 AI 引导的自主性领域中，核心挑战在于使智能体能够根据自然语言指令，在从未见过的环境中实现现实且有效的导航。我们提出了 UAV-VLN，这是一个针对无人机（UAV）的全新端到端视觉语言导航（VLN）框架，通过无缝融合大型语言模型（LLMs）与视觉感知功能，实现人机交互式导航。我们的系统能够解析自由形式的自然语言指令，将其与视觉观察结果相结合，并在各种环境中规划可行的空中轨迹。
    UAV-VLN 利用 LLM 的常识推理能力来解析高层次的语义目标，同时视觉模型负责检测和定位环境中语义相关的物体。通过融合这些模态信息，无人机能够推理空间关系、消除人类指令中的歧义，并在最小的任务特定监督下规划上下文感知的行为。为确保决策的稳健性和可解释性，该框架包含了一种跨模态接地机制，用于将语言意图与视觉上下文对齐。
    我们在多种室内外导航场景中对 UAV-VLN 进行了评估，展示了其在最少任务特定训练情况下，对新指令和新环境的泛化能力。实验结果表明，该框架在指令遵循准确性和轨迹效率方面均有显著提升，凸显了基于 LLM 的视觉语言界面在实现安全、直观且通用的无人机自主性方面的潜力。

> A core challenge in AI-guided autonomy is enabling agents to navigate realistically and effectively in previously unseen environments based on natural language commands. We propose UAV-VLN, a novel end-to-end Vision-Language Navigation (VLN) framework for Unmanned Aerial Vehicles (UAVs) that seamlessly integrates Large Language Models (LLMs) with visual perception to facilitate human-interactive navigation. Our system interprets free-form natural language instructions, grounds them into visual observations, and plans feasible aerial trajectories in diverse environments.
  UAV-VLN leverages the common-sense reasoning capabilities of LLMs to parse high-level semantic goals, while a vision model detects and localizes semantically relevant objects in the environment. By fusing these modalities, the UAV can reason about spatial relationships, disambiguate references in human instructions, and plan context-aware behaviors with minimal task-specific supervision. To ensure robust and interpretable decision-making, the framework includes a cross-modal grounding mechanism that aligns linguistic intent with visual context.
  We evaluate UAV-VLN across diverse indoor and outdoor navigation scenarios, demonstrating its ability to generalize to novel instructions and environments with minimal task-specific training. Our results show significant improvements in instruction-following accuracy and trajectory efficiency, highlighting the potential of LLM-driven vision-language interfaces for safe, intuitive, and generalizable UAV autonomy.

[Arxiv](https://arxiv.org/abs/2504.21432)