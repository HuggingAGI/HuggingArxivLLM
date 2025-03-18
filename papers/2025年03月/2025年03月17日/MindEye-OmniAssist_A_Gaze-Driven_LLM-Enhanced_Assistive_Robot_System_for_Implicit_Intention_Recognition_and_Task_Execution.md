# MindEye-OmniAssist：基于注视驱动的LLM增强型辅助机器人系统，用于隐式意图识别与任务执行

发布时间：2025年03月17日

`LLM应用` `人机交互` `机器人`

> MindEye-OmniAssist: A Gaze-Driven LLM-Enhanced Assistive Robot System for Implicit Intention Recognition and Task Execution

# 摘要

> 基于注视的人机交互在辅助机器人系统中展现出广阔前景。然而，当前的基于注视的辅助系统仅限于帮助用户完成基础抓取动作，支持范围有限。同时，受限的意图识别能力也制约了系统提供多样化辅助功能的能力。本文提出了一种由大型语言模型（LLM）和视觉基础模型（VFM）驱动的开放隐式意图识别框架，能够处理注视输入并识别不限于预定义场景的用户意图。我们还实现了基于注视的LLM增强型辅助机器人系统（MindEye-OmniAssist），该系统通过注视识别用户意图并协助完成任务。系统利用开放词汇对象检测器、意图识别网络和LLM推断用户完整意图，并结合眼球运动反馈和LLM生成动作序列，帮助用户完成任务。真实世界实验中，系统在多种未定义任务中取得了41/55的成功率。初步结果显示，该方法有望通过支持更复杂多样的任务，提供更用户友好的交互界面，并显著提升辅助系统的通用性和有效性。

> A promising effective human-robot interaction in assistive robotic systems is gaze-based control. However, current gaze-based assistive systems mainly help users with basic grasping actions, offering limited support. Moreover, the restricted intent recognition capability constrains the assistive system's ability to provide diverse assistance functions. In this paper, we propose an open implicit intention recognition framework powered by Large Language Model (LLM) and Vision Foundation Model (VFM), which can process gaze input and recognize user intents that are not confined to predefined or specific scenarios. Furthermore, we implement a gaze-driven LLM-enhanced assistive robot system (MindEye-OmniAssist) that recognizes user's intentions through gaze and assists in completing task. To achieve this, the system utilizes open vocabulary object detector, intention recognition network and LLM to infer their full intentions. By integrating eye movement feedback and LLM, it generates action sequences to assist the user in completing tasks. Real-world experiments have been conducted for assistive tasks, and the system achieved an overall success rate of 41/55 across various undefined tasks. Preliminary results show that the proposed method holds the potential to provide a more user-friendly human-computer interaction interface and significantly enhance the versatility and effectiveness of assistive systems by supporting more complex and diverse task.

[Arxiv](https://arxiv.org/abs/2503.13250)