# VLAS：用于定制化机器人操作的语音指令视觉-语言-动作模型

发布时间：2025年02月19日

`RAG` `机器人` `语音交互`

> VLAS: Vision-Language-Action Model With Speech Instructions For Customized Robot Manipulation

# 摘要

> 视觉-语言-动作模型（VLAs）凭借其端到端的设计和出色的表现，在机器人操作领域备受青睐。然而，现有VLAs过度依赖仅支持文本指令的视觉-语言模型（VLMs），忽视了更自然的语音交互模式在人机交互中的潜力。传统语音整合方法通常需要独立的语音识别系统，这不仅增加了模型复杂性，还导致了错误传播。此外，转录过程会丢失原始语音中的非语义信息（如语音特征），这些信息可能对机器人完成定制任务至关重要。

为了解决这些问题，我们提出了VLAS——一种全新的端到端视觉-语言-动作模型，将语音识别直接整合到机器人策略模型中。VLAS通过内部语音-文本对齐理解语音指令，并生成相应动作完成任务。我们还推出了两个新数据集SQA和CSI，支持语音指令的三阶段微调，赋予VLAS跨文本、图像、语音和机器人动作的多模态交互能力。更进一步，我们设计了一种基于语音检索增强生成（RAG）的范式，使模型能够有效处理需要个体特定知识的任务。

实验结果表明，VLAS能够有效完成多样语音指令下的机器人操作任务，为用户提供无缝且个性化的交互体验。

> Vision-language-action models (VLAs) have become increasingly popular in robot manipulation for their end-to-end design and remarkable performance. However, existing VLAs rely heavily on vision-language models (VLMs) that only support text-based instructions, neglecting the more natural speech modality for human-robot interaction. Traditional speech integration methods usually involves a separate speech recognition system, which complicates the model and introduces error propagation. Moreover, the transcription procedure would lose non-semantic information in the raw speech, such as voiceprint, which may be crucial for robots to successfully complete customized tasks. To overcome above challenges, we propose VLAS, a novel end-to-end VLA that integrates speech recognition directly into the robot policy model. VLAS allows the robot to understand spoken commands through inner speech-text alignment and produces corresponding actions to fulfill the task. We also present two new datasets, SQA and CSI, to support a three-stage tuning process for speech instructions, which empowers VLAS with the ability of multimodal interaction across text, image, speech, and robot actions. Taking a step further, a voice retrieval-augmented generation (RAG) paradigm is designed to enable our model to effectively handle tasks that require individual-specific knowledge. Our extensive experiments show that VLAS can effectively accomplish robot manipulation tasks with diverse speech commands, offering a seamless and customized interaction experience.

[Arxiv](https://arxiv.org/abs/2502.13508)