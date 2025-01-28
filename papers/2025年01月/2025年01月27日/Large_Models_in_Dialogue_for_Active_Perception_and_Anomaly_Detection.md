# 大型模型在对话中的主动感知与异常检测

发布时间：2025年01月27日

`Agent

理由：这篇论文描述了一个利用大型语言模型（LLMs）来控制无人机进行自主空中监测的系统。该系统通过LLM与深度学习模型的对话来主动控制无人机，提升感知与异常检测的准确性。这种系统涉及到自主决策和任务执行，符合“Agent”类别的定义，即能够自主执行任务的智能体。` `无人机` `异常检测`

> Large Models in Dialogue for Active Perception and Anomaly Detection

# 摘要

> # 自主空中监测
自主空中监测旨在从人类难以进入的区域收集信息，并识别远距离或未遇见的异常。本文提出了一种新颖框架，利用大型语言模型（LLMs）的先进能力，在新场景中主动收集信息并检测异常。我们采用基于LLM的模型对话方法，两个深度学习模型通过对话主动控制无人机，提升感知与异常检测的准确性。实验在高保真模拟环境中进行，LLM接收预定义的自然语言移动指令并转化为可执行代码。同时，我们部署了多模态视觉问答（VQA）模型，负责视觉问答与图像描述。通过模型对话，LLM在操控无人机探索场景时提出探索性问题，实现了主动感知的新方式。借助LLM的推理能力，我们生成了比静态感知方法更详细的场景描述。此外，该方法还用于异常检测，实验结果证明了其在预警潜在危险方面的有效性。

> Autonomous aerial monitoring is an important task aimed at gathering information from areas that may not be easily accessible by humans. At the same time, this task often requires recognizing anomalies from a significant distance or not previously encountered in the past. In this paper, we propose a novel framework that leverages the advanced capabilities provided by Large Language Models (LLMs) to actively collect information and perform anomaly detection in novel scenes. To this end, we propose an LLM based model dialogue approach, in which two deep learning models engage in a dialogue to actively control a drone to increase perception and anomaly detection accuracy. We conduct our experiments in a high fidelity simulation environment where an LLM is provided with a predetermined set of natural language movement commands mapped into executable code functions. Additionally, we deploy a multimodal Visual Question Answering (VQA) model charged with the task of visual question answering and captioning. By engaging the two models in conversation, the LLM asks exploratory questions while simultaneously flying a drone into different parts of the scene, providing a novel way to implement active perception. By leveraging LLMs reasoning ability, we output an improved detailed description of the scene going beyond existing static perception approaches. In addition to information gathering, our approach is utilized for anomaly detection and our results demonstrate the proposed methods effectiveness in informing and alerting about potential hazards.

[Arxiv](https://arxiv.org/abs/2501.16300)