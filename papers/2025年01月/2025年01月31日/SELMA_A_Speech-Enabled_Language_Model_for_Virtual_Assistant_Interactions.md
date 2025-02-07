# SELMA: 语音驱动的虚拟助手交互语言模型

发布时间：2025年01月31日

`LLM应用

理由：这篇论文介绍了SELMA，一个语音增强语言模型，用于虚拟助手交互。它集成了音频和文本输入，并在一个端到端模型中处理多个任务。这属于LLM在实际应用中的具体实现，特别是用于虚拟助手交互的场景，因此归类为LLM应用。` `虚拟助手` `语音处理`

> SELMA: A Speech-Enabled Language Model for Virtual Assistant Interactions

# 摘要

> 我们提出了SELMA，一个语音增强语言模型，用于虚拟助手交互，它将音频和文本输入集成到LLM中。SELMA在一个端到端模型中同时处理三个主要任务和两个辅助任务。我们采用低秩适应模块进行参数高效训练，并通过特征池化策略提升全局模式识别能力。实验结果显示，SELMA不仅简化了虚拟助手的输入处理流程，还在VT检测和DDSD任务上分别实现了64%和22%的性能提升，同时保持了接近基线的词错误率。

> In this work, we present and evaluate SELMA, a Speech-Enabled Language Model for virtual Assistant interactions that integrates audio and text as inputs to a Large Language Model (LLM). SELMA is designed to handle three primary and two auxiliary tasks related to interactions with virtual assistants simultaneously within a single end-to-end model. We employ low-rank adaptation modules for parameter-efficient training of both the audio encoder and the LLM. Additionally, we implement a feature pooling strategy enabling the system to recognize global patterns and improve accuracy on tasks less reliant on individual sequence elements. Experimental results on Voice Trigger (VT) detection, Device-Directed Speech Detection (DDSD), and Automatic Speech Recognition (ASR), demonstrate that our approach both simplifies the typical input processing pipeline of virtual assistants significantly and also improves performance compared to dedicated models for each individual task. SELMA yields relative Equal-Error Rate improvements of 64% on the VT detection task, and 22% on DDSD, while also achieving word error rates close to the baseline.

[Arxiv](https://arxiv.org/abs/2501.19377)