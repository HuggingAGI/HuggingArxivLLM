# Investigating and Enhancing Vision-Audio Capability in Omnimodal Large Language Models
研究并提升全模态大型语言模型的视觉与音频能力

发布时间：2025年02月26日

`LLM应用` `多模态` `视觉音频`

> Investigating and Enhancing Vision-Audio Capability in Omnimodal Large Language Models

# 摘要

> 多模态大型语言模型 (OLLMs) 在视觉与文本的整合上取得了显著进展，但在视觉与音频的整合上仍面临挑战，处理音频查询时的表现往往不如处理文本查询。这种差距主要源于训练过程中视觉与音频模态的对齐不足，导致使用音频查询时对视觉信息关注不够。为解决这一问题，我们提出了一种自知识蒸馏 (Self-KD) 训练方法，其中 OLLM 的视觉-文本组件作为教师，视觉-音频组件作为学生。这使模型能够以与处理文本类似的方式处理音频。实验结果表明，Self-KD 是一种有效的方法，通过从视觉-文本组件中学习来增强 OLLM 的视觉-音频能力，从而改善音频与图像的交互，提升多模态任务的性能。

> Omnimodal Large Language Models (OLLMs) have shown significant progress in integrating vision and text, but still struggle with integrating vision and audio, often exhibiting suboptimal performance when processing audio queries compared to text queries. This disparity is primarily due to insufficient alignment between vision and audio modalities during training, leading to inadequate attention to visual information when using audio queries. To mitigate this issue, we propose a Self-Knowledge Distillation (Self-KD) training method where the vision-text component of the OLLM serves as the teacher and the vision-audio component as the student. This enables the model to process audio in a manner analogous to its text processing. Our experimental results demonstrate that Self-KD is an effective method for enhancing the vision-audio capabilities of OLLMs by learning from the vision-text components, which subsequently improves the interaction between audio and images and results in improved performance on multimodal tasks.

[Arxiv](https://arxiv.org/abs/2503.00059)