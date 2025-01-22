# InsTALL: 多模态大语言模型驱动的上下文感知教学任务助手

发布时间：2025年01月21日

`Agent

理由：这篇论文描述了一个基于多模态大型语言模型的虚拟助手InsTALL，它能够通过在线视觉流实时响应用户的查询，并具备情境感知能力。这种助手可以被视为一种智能代理（Agent），因为它能够根据对任务和动作的理解提供精准帮助，并且能够自动提取视频中的任务图以辅助任务执行。因此，这篇论文更适合归类为Agent。` `虚拟助手` `多模态学习`

> InsTALL: Context-aware Instructional Task Assistance with Multi-modal Large Language Models

# 摘要

> 生成模型能力的提升为构建多模态虚拟助手提供了可能，这些助手不仅能处理语言，还能利用其他模态。通过观察人类执行多步骤任务，我们可以构建具有情境感知能力的助手，使其能够根据对任务和动作的理解提供精准帮助。本文提出的InsTALL助手基于多模态大型语言模型，利用在线视觉流（如屏幕共享或视频录制）实时响应用户与任务相关的查询。InsTALL通过1）在任务视频和文本数据上训练多模态模型，2）自动提取视频中的任务图并在训练和推理中使用，实现了高效的任务辅助。实验表明，InsTALL在多模态活动理解的子任务——任务识别（TR）、动作识别（AR）、下一个动作预测（AP）和计划预测（PP）——中表现优异，并在自动错误识别的两个新任务上超越了现有基线。

> The improved competence of generative models can help building multi-modal virtual assistants that leverage modalities beyond language. By observing humans performing multi-step tasks, one can build assistants that have situational awareness of actions and tasks being performed, enabling them to cater assistance based on this understanding. In this paper, we develop a Context-aware Instructional Task Assistant with Multi-modal Large Language Models (InsTALL) that leverages an online visual stream (e.g. a user's screen share or video recording) and responds in real-time to user queries related to the task at hand. To enable useful assistance, InsTALL 1) trains a multi-modal model on task videos and paired textual data, and 2) automatically extracts task graph from video data and leverages it at training and inference time. We show InsTALL achieves state-of-the-art performance across proposed sub-tasks considered for multimodal activity understanding -- task recognition (TR), action recognition (AR), next action prediction (AP), and plan prediction (PP) -- and outperforms existing baselines on two novel sub-tasks related to automatic error identification.

[Arxiv](https://arxiv.org/abs/2501.12231)