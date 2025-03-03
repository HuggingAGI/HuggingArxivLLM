# RoboBrain：从抽象到具体的统一机器人操作大脑模型

发布时间：2025年02月28日

`LLM应用` `机器人` `人工智能`

> RoboBrain: A Unified Brain Model for Robotic Manipulation from Abstract to Concrete

# 摘要

> 近期，多模态大语言模型（MLLMs）在多个跨模态场景中展现出了非凡的能力。然而，在机器人场景中，尤其是长时域操作任务中，这些模型的表现却暴露出显著的局限性。这些局限性源于当前MLLMs缺少三项关键的机器人脑功能：规划能力，即分解复杂操作指令为可管理子任务的能力；可及性感知，识别并理解交互对象的可及性；以及轨迹预测，预见成功执行所需完整操作轨迹的能力。为了将机器人脑的核心能力从抽象概念具象化为实际应用，我们推出了ShareRobot，一个高质量异构数据集，标注了任务规划、物体可及性及末端执行器轨迹等多维信息。该数据集的多样性和准确性经过三位人工标注员的精心打磨。基于此数据集，我们开发了RoboBrain，一款基于MLLM的模型，整合了机器人与通用多模态数据，采用多阶段训练策略，并引入长视频和高分辨率图像以提升其机器人操作能力。大量实验证明，RoboBrain在各类机器人任务中达到了目前最优的性能水平，充分展现了其在推进机器人脑能力方面的潜力。

> Recent advancements in Multimodal Large Language Models (MLLMs) have shown remarkable capabilities across various multimodal contexts. However, their application in robotic scenarios, particularly for long-horizon manipulation tasks, reveals significant limitations. These limitations arise from the current MLLMs lacking three essential robotic brain capabilities: Planning Capability, which involves decomposing complex manipulation instructions into manageable sub-tasks; Affordance Perception, the ability to recognize and interpret the affordances of interactive objects; and Trajectory Prediction, the foresight to anticipate the complete manipulation trajectory necessary for successful execution. To enhance the robotic brain's core capabilities from abstract to concrete, we introduce ShareRobot, a high-quality heterogeneous dataset that labels multi-dimensional information such as task planning, object affordance, and end-effector trajectory. ShareRobot's diversity and accuracy have been meticulously refined by three human annotators. Building on this dataset, we developed RoboBrain, an MLLM-based model that combines robotic and general multi-modal data, utilizes a multi-stage training strategy, and incorporates long videos and high-resolution images to improve its robotic manipulation capabilities. Extensive experiments demonstrate that RoboBrain achieves state-of-the-art performance across various robotic tasks, highlighting its potential to advance robotic brain capabilities.

[Arxiv](https://arxiv.org/abs/2502.21257)