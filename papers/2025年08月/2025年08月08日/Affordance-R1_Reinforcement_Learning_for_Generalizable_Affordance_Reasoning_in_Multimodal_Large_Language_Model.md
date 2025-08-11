# Affordance-R1：多模态大型语言模型中强化学习驱动的可推广Affordance推理方法

发布时间：2025年08月08日

`Agent` `机器人学` `人机交互`

> Affordance-R1: Reinforcement Learning for Generalizable Affordance Reasoning in Multimodal Large Language Model

# 摘要

> # 可操作性定位
可操作性定位专注于预测与机器人执行动作相关的物体特定区域，是人机交互、人与物体交互、具身操作和具身感知等领域的关键技术。现有模型往往忽视不同物体之间共享的可操作性，主要原因在于它们缺乏链式思维（CoT）推理能力，这限制了模型的领域外泛化和显式推理能力。

为了解决这一问题，我们提出了Affordance-R1——首个将认知CoT引导的组相对策略优化（GRPO）集成到强化学习框架中的统一可操作性定位方法。具体而言，我们设计了一个复杂的可操作性函数，通过整合格式、感知和认知奖励，有效指导优化方向。此外，我们还构建了一个高质量的以可操作性为中心的推理数据集ReasonAff，为模型训练提供了有力支持。

通过仅使用强化学习和GRPO进行训练，且无需显式推理数据，Affordance-R1实现了稳健的零样本泛化能力，并展现了测试时推理能力的涌现特性。实验结果表明，我们的模型不仅超越了现有方法，还展现出开放世界的泛化潜力。值得注意的是，Affordance-R1是首个将基于GRPO的强化学习与推理结合到可操作性推理中的方法。我们的方法代码和数据集已发布在GitHub仓库：https://github.com/hq-King/Affordance-R1。

> Affordance grounding focuses on predicting the specific regions of objects that are associated with the actions to be performed by robots. It plays a vital role in the fields of human-robot interaction, human-object interaction, embodied manipulation, and embodied perception. Existing models often neglect the affordance shared among different objects because they lack the Chain-of-Thought(CoT) reasoning abilities, limiting their out-of-domain (OOD) generalization and explicit reasoning capabilities. To address these challenges, we propose Affordance-R1, the first unified affordance grounding framework that integrates cognitive CoT guided Group Relative Policy Optimization (GRPO) within a reinforcement learning paradigm. Specifically, we designed a sophisticated affordance function, which contains format, perception, and cognition rewards to effectively guide optimization directions. Furthermore, we constructed a high-quality affordance-centric reasoning dataset, ReasonAff, to support training. Trained exclusively via reinforcement learning with GRPO and without explicit reasoning data, Affordance-R1 achieves robust zero-shot generalization and exhibits emergent test-time reasoning capabilities. Comprehensive experiments demonstrate that our model outperforms well-established methods and exhibits open-world generalization. To the best of our knowledge, Affordance-R1 is the first to integrate GRPO-based RL with reasoning into affordance reasoning. The code of our method and our dataset is released on https://github.com/hq-King/Affordance-R1.

[Arxiv](https://arxiv.org/abs/2508.06206)