# STeCa：大型语言模型代理学习的分步轨迹校准

发布时间：2025年02月20日

`Agent` `人工智能`

> STeCa: Step-level Trajectory Calibration for LLM Agent Learning

# 摘要

> 基于大型语言模型（LLM）的代理在处理复杂任务时展现出巨大潜力，通过动态与环境交互来完成任务。目前的研究主要集中在从专家演示中进行行为克隆以及通过探索性轨迹采样进行偏好学习。然而，在处理长周期任务时，次优动作会逐步累积，导致代理偏离正确的任务轨迹，这是现有方法的痛点。为了解决这一问题，我们提出了Step-Level Trajectory Calibration（STeCa），一种全新的LLM代理学习框架。STeCa通过探索过程中的步级奖励比较来识别次优动作，并利用LLM驱动的反思构建校准轨迹，帮助代理从改进的决策过程中学习。这些校准轨迹与成功的轨迹数据一起用于强化训练。大量实验表明，STeCa显著优于现有方法。进一步分析表明，步级校准使代理能够以更高的鲁棒性完成任务。我们的代码和数据可在GitHub上获取：https://github.com/WangHanLinHenry/STeCa。

> Large language model (LLM)-based agents have shown promise in tackling complex tasks by interacting dynamically with the environment. Existing work primarily focuses on behavior cloning from expert demonstrations and preference learning through exploratory trajectory sampling. However, these methods often struggle in long-horizon tasks, where suboptimal actions accumulate step by step, causing agents to deviate from correct task trajectories. To address this, we highlight the importance of timely calibration and the need to automatically construct calibration trajectories for training agents. We propose Step-Level Trajectory Calibration (STeCa), a novel framework for LLM agent learning. Specifically, STeCa identifies suboptimal actions through a step-level reward comparison during exploration. It constructs calibrated trajectories using LLM-driven reflection, enabling agents to learn from improved decision-making processes. These calibrated trajectories, together with successful trajectory data, are utilized for reinforced training. Extensive experiments demonstrate that STeCa significantly outperforms existing methods. Further analysis highlights that step-level calibration enables agents to complete tasks with greater robustness. Our code and data are available at https://github.com/WangHanLinHenry/STeCa.

[Arxiv](https://arxiv.org/abs/2502.14276)