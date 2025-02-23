# Mem2Ego：通过全局到自我记忆增强视觉语言模型，助力长时地平线具身导航

发布时间：2025年02月19日

`Agent` `智能体导航` `视觉语言模型`

> Mem2Ego: Empowering Vision-Language Models with Global-to-Ego Memory for Long-Horizon Embodied Navigation

# 摘要

> 大型语言模型（LLMs）和视觉语言模型（VLMs）的最新进展使它们成为具身导航的强大工具，使智能体能够利用常识和空间推理在陌生环境中进行高效探索。现有的基于LLM的方法将全局记忆（如语义或拓扑地图）转换为语言描述以指导导航。虽然这提高了效率并减少了冗余探索，但基于语言表示的几何信息丢失阻碍了空间推理，尤其是在复杂环境中。为了解决这一问题，基于VLM的方法直接处理以自我为中心的视觉输入以选择探索的最佳方向。然而，仅依赖第一人称视角使导航成为一个部分观察的决策问题，在复杂环境中导致次优决策。在本文中，我们提出了一种新颖的基于视觉语言模型（VLM）的导航框架，通过自适应检索全局记忆模块中的任务相关线索，并将其与智能体的以自我为中心的观察相结合来解决这些挑战。通过动态对齐全局上下文信息与局部感知，我们的方法增强了长期任务中的空间推理和决策。实验结果表明，所提出的方法在物体导航任务中超越了之前的最先进方法，为具身导航提供了一种更有效和可扩展的解决方案。

> Recent advancements in Large Language Models (LLMs) and Vision-Language Models (VLMs) have made them powerful tools in embodied navigation, enabling agents to leverage commonsense and spatial reasoning for efficient exploration in unfamiliar environments. Existing LLM-based approaches convert global memory, such as semantic or topological maps, into language descriptions to guide navigation. While this improves efficiency and reduces redundant exploration, the loss of geometric information in language-based representations hinders spatial reasoning, especially in intricate environments. To address this, VLM-based approaches directly process ego-centric visual inputs to select optimal directions for exploration. However, relying solely on a first-person perspective makes navigation a partially observed decision-making problem, leading to suboptimal decisions in complex environments. In this paper, we present a novel vision-language model (VLM)-based navigation framework that addresses these challenges by adaptively retrieving task-relevant cues from a global memory module and integrating them with the agent's egocentric observations. By dynamically aligning global contextual information with local perception, our approach enhances spatial reasoning and decision-making in long-horizon tasks. Experimental results demonstrate that the proposed method surpasses previous state-of-the-art approaches in object navigation tasks, providing a more effective and scalable solution for embodied navigation.

[Arxiv](https://arxiv.org/abs/2502.14254)