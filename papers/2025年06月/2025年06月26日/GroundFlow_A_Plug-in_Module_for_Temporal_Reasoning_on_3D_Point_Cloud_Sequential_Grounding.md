# GroundFlow：用于3D点云序列接地的时序推理插件模块

发布时间：2025年06月26日

`其他` `计算机视觉` `机器人`

> GroundFlow: A Plug-in Module for Temporal Reasoning on 3D Point Cloud Sequential Grounding

# 摘要

> 3D点云中的顺序定位任务（SG3D）通过遵循描述日常活动的详细步骤文本指令，依次定位物体序列。目前的3D视觉定位（3DVG）方法将多步骤的文本指令视为整体处理，未能有效提取各步骤中的时序信息。然而，SG3D中的指令常使用“它”、“这里”和“相同的”等代词使表达更简洁，这意味着定位方法需理解上下文并从先前步骤中检索信息以准确定位物体序列。由于缺乏有效模块来收集相关历史信息，现有3DVG方法在适应SG3D任务时面临重大挑战。为解决这一问题，我们提出了GroundFlow——一个用于3D点云顺序定位任务的时间推理插件模块。首先，在SG3D基准测试中，集成GroundFlow可显著提升3DVG基线方法的性能（+7.5%和+10.2%），甚至超越了在多个数据集上预训练的3D大型语言模型。此外，我们基于当前指令的相关性，有选择地提取短期和长期步骤信息，使GroundFlow能够全面审视历史信息，并在步骤数量增加时保持其时间理解优势。总体而言，我们的工作为现有3DVG模型引入了时间推理能力，并在SG3D基准测试中实现了跨五个数据集的最先进性能。

> Sequential grounding in 3D point clouds (SG3D) refers to locating sequences of objects by following text instructions for a daily activity with detailed steps. Current 3D visual grounding (3DVG) methods treat text instructions with multiple steps as a whole, without extracting useful temporal information from each step. However, the instructions in SG3D often contain pronouns such as "it", "here" and "the same" to make language expressions concise. This requires grounding methods to understand the context and retrieve relevant information from previous steps to correctly locate object sequences. Due to the lack of an effective module for collecting related historical information, state-of-the-art 3DVG methods face significant challenges in adapting to the SG3D task. To fill this gap, we propose GroundFlow -- a plug-in module for temporal reasoning on 3D point cloud sequential grounding. Firstly, we demonstrate that integrating GroundFlow improves the task accuracy of 3DVG baseline methods by a large margin (+7.5\% and +10.2\%) in the SG3D benchmark, even outperforming a 3D large language model pre-trained on various datasets. Furthermore, we selectively extract both short-term and long-term step information based on its relevance to the current instruction, enabling GroundFlow to take a comprehensive view of historical information and maintain its temporal understanding advantage as step counts increase. Overall, our work introduces temporal reasoning capabilities to existing 3DVG models and achieves state-of-the-art performance in the SG3D benchmark across five datasets.

[Arxiv](https://arxiv.org/abs/2506.21188)