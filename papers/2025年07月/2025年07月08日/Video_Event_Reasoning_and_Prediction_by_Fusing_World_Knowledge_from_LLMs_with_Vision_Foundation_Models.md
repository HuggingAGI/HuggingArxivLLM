# 融合大型语言模型中的世界知识与视觉基础模型，实现视频事件推理与预测

发布时间：2025年07月08日

`LLM应用` `机器人学` `人机交互`

> Video Event Reasoning and Prediction by Fusing World Knowledge from LLMs with Vision Foundation Models

# 摘要

> 现有的视频理解模型虽然擅长识别“正在发生什么”，但在因果推理和未来预测等高级认知任务上表现不足，这一局限性源于其缺乏常识性世界知识。为解决这一问题，我们提出了一种创新框架，将强大的视觉基础模型（VFM）用于深度视觉感知，与作为知识驱动推理核心的大规模语言模型（LLM）协同融合。我们的关键技术突破是一个复杂的融合模块，灵感源自Q-Former架构，它将复杂的时空和以对象为中心的视觉特征提炼成简洁、与语言对齐的表示形式，使LLM能够将其推理过程有效地锚定在直接的视觉证据上。模型通过两阶段策略进行训练，首先在视频-文本数据上进行大规模对齐预训练，然后在经过精心策划的数据集上进行有针对性的指令微调，以激发高级推理和预测能力。实验结果表明，我们的模型在多个具有挑战性的基准测试中达到了目前最优水平。值得注意的是，它在未见过的推理任务上表现出色的零样本迁移能力，而深度消融研究验证了每个架构组件的关键贡献。这项工作推动了机器感知从简单的识别迈向真正的认知理解，为机器人学、人机交互等领域中更智能、更强大的AI系统铺平了道路。


> Current video understanding models excel at recognizing "what" is happening but fall short in high-level cognitive tasks like causal reasoning and future prediction, a limitation rooted in their lack of commonsense world knowledge. To bridge this cognitive gap, we propose a novel framework that synergistically fuses a powerful Vision Foundation Model (VFM) for deep visual perception with a Large Language Model (LLM) serving as a knowledge-driven reasoning core. Our key technical innovation is a sophisticated fusion module, inspired by the Q-Former architecture, which distills complex spatiotemporal and object-centric visual features into a concise, language-aligned representation. This enables the LLM to effectively ground its inferential processes in direct visual evidence. The model is trained via a two-stage strategy, beginning with large-scale alignment pre-training on video-text data, followed by targeted instruction fine-tuning on a curated dataset designed to elicit advanced reasoning and prediction skills. Extensive experiments demonstrate that our model achieves state-of-the-art performance on multiple challenging benchmarks. Notably, it exhibits remarkable zero-shot generalization to unseen reasoning tasks, and our in-depth ablation studies validate the critical contribution of each architectural component. This work pushes the boundary of machine perception from simple recognition towards genuine cognitive understanding, paving the way for more intelligent and capable AI systems in robotics, human-computer interaction, and beyond.

[Arxiv](https://arxiv.org/abs/2507.05822)