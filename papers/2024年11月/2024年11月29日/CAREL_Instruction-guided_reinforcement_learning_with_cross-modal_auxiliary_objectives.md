# CAREL：具备跨模态辅助目标的指令引导式强化学习

发布时间：2024年11月29日

`Agent` `自动化`

> CAREL: Instruction-guided reinforcement learning with cross-modal auxiliary objectives

# 摘要

> 在环境中为指令奠定基础，是解决语言引导的目标达成强化学习问题的关键一步。在自动化强化学习里，关键在于增强模型在各类任务和环境中的泛化能力。在目标达成的情境中，智能体必须在环境背景下领会指令的不同部分，从而成功完成整个任务。在本研究中，我们提出了 CAREL（跨模态辅助强化学习）这一新框架，借助受视频 - 文本检索文献启发的辅助损失函数以及名为指令跟踪的新方法来解决此问题，该方法能自动追踪环境中的进展。我们的实验结果显示，此框架在多模态强化学习问题中具备出色的样本效率和系统泛化能力。我们的代码库在此处可获取。

> Grounding the instruction in the environment is a key step in solving language-guided goal-reaching reinforcement learning problems. In automated reinforcement learning, a key concern is to enhance the model's ability to generalize across various tasks and environments. In goal-reaching scenarios, the agent must comprehend the different parts of the instructions within the environmental context in order to complete the overall task successfully. In this work, we propose CAREL (Cross-modal Auxiliary REinforcement Learning) as a new framework to solve this problem using auxiliary loss functions inspired by video-text retrieval literature and a novel method called instruction tracking, which automatically keeps track of progress in an environment. The results of our experiments suggest superior sample efficiency and systematic generalization for this framework in multi-modal reinforcement learning problems. Our code base is available here.

[Arxiv](https://arxiv.org/abs/2411.19787)