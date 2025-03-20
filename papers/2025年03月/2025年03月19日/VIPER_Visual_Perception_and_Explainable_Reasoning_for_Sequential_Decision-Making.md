# VIPER：为序列决策提供视觉感知与可解释推理

发布时间：2025年03月19日

`LLM应用` `人工智能` `机器人技术`

> VIPER: Visual Perception and Explainable Reasoning for Sequential Decision-Making

# 摘要

> 虽然大型语言模型（LLMs）在文本推理方面表现出色，视觉语言模型（VLMs）在视觉感知方面也非常有效，但将这些模型应用于基于视觉指令的规划仍是一个广泛未解决的问题。本文中，我们提出了VIPER，一个全新的多模态指令规划框架，它巧妙地结合了基于VLM的感知与基于LLM的推理。我们的方法采用模块化流水线设计，其中冻结的VLM生成图像观察的文本描述，随后由LLM策略根据任务目标处理这些描述以预测动作。通过行为克隆和强化学习对推理模块进行微调，我们显著提升了代理的决策能力。在ALFWorld基准上的实验结果表明，VIPER不仅显著优于现有的基于视觉指令的规划器，还缩小了与纯文本基线的差距。通过利用文本作为中间表示，VIPER不仅增强了可解释性，还为对感知和推理组件进行细致分析铺平了道路。

> While Large Language Models (LLMs) excel at reasoning on text and Vision-Language Models (VLMs) are highly effective for visual perception, applying those models for visual instruction-based planning remains a widely open problem. In this paper, we introduce VIPER, a novel framework for multimodal instruction-based planning that integrates VLM-based perception with LLM-based reasoning. Our approach uses a modular pipeline where a frozen VLM generates textual descriptions of image observations, which are then processed by an LLM policy to predict actions based on the task goal. We fine-tune the reasoning module using behavioral cloning and reinforcement learning, improving our agent's decision-making capabilities. Experiments on the ALFWorld benchmark show that VIPER significantly outperforms state-of-the-art visual instruction-based planners while narrowing the gap with purely text-based oracles. By leveraging text as an intermediate representation, VIPER also enhances explainability, paving the way for a fine-grained analysis of perception and reasoning components.

[Arxiv](https://arxiv.org/abs/2503.15108)