# 视频大型多模态模型：学会质疑还是固守己见？——一项关于可反驳视频蕴含的探究

发布时间：2025年06月27日

`LLM应用` `多模态`

> Can Video Large Multimodal Models Think Like Doubters-or Double-Down: A Study on Defeasible Video Entailment

# 摘要

> 视频大型多模态模型（VLMMs）在理解视频内容方面取得了显著进展，但其抽象和自适应推理能力仍有待提升，特别是在面对新信息时的解释调整能力。现实中，结论并非一成不变，额外背景信息可能加强或削弱初始推断。为此，我们提出了可反驳的视频蕴含任务（DVidE），挑战模型像怀疑者一样思考，持续根据新证据更新推理。在DVidE中，给定视频前提和文本假设，模型需判断新更新是强化还是弱化假设（分类版本），或生成连贯更新以修改蕴含关系（生成版本）。针对分类任务，我们提出了反事实推理链框架，通过反事实推理、ASR增强视频内容和推理优化减少偏差。生成任务方面，我们结合ASR输出与大型语言模型（LLM），生成与预期目标一致的连贯更新。此外，我们开发了一个全新基准数据集，包含强化/弱化标注，并设计了基于LLM的评估指标，专为生成性能评估打造。实验结果表明，我们的方法显著提升了VLMMs的动态推理能力，充分验证了方法的有效性。

> Video Large Multimodal Models (VLMMs) have made impressive strides in understanding video content, but they often struggle with abstract and adaptive reasoning-the ability to revise their interpretations when new information emerges. In reality, conclusions are rarely set in stone; additional context can strengthen or weaken an initial inference. To address this, we introduce Defeasible Video Entailment (DVidE), a new task that challenges models to think like doubters, constantly updating their reasoning based on evolving evidence. In DVidE, given a video premise and a textual hypothesis, models must determine whether a new update strengthens or weakens the hypothesis (classification version) or generate a coherent update that modifies the entailment relationship (generation version). For solving the classification task, we propose the Chain of Counterfactual Thought framework, utilizing counterfactual reasoning, ASR-enhanced video content, and rationale refinement to reduce inference bias. For the generation task, we develop a framework that combines ASR output with a Large Language Model (LLM) to produce coherent, contextually relevant updates aligned with the intended strengthener or weakener goals. Additionally, we introduce a novel benchmark dataset, with strengthener/weakener annotations and an LLM-based evaluation metric specifically designed for assessing generative performance. Experimental results demonstrate significant improvements, highlighting our proposed method in enhancing dynamic reasoning capabilities of VLMMs.

[Arxiv](https://arxiv.org/abs/2506.22385)