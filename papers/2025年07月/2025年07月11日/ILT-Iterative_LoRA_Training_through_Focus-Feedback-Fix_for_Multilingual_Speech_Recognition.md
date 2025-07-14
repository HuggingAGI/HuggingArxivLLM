# # ILT：聚焦-反馈-修复驱动的迭代LoRA训练在多语言语音识别中的应用

发布时间：2025年07月11日

`LLM应用` `语音技术` `语音识别`

> ILT-Iterative LoRA Training through Focus-Feedback-Fix for Multilingual Speech Recognition

# 摘要

> 大型语言模型与自动语音识别系统的深度融合已成为极具应用价值的研究方向。针对低秩适配（LoRA）在监督微调过程中常见的过拟合问题，我们提出了一种创新的训练范式——迭代LoRA训练（ILT），并结合迭代伪标签策略，显著提升了模型性能的理论上限。基于Whisper-large-v3和Qwen2-Audio模型，我们采用专注训练、反馈训练和修复训练三阶段流程进行系统性实验。实验结果充分证明了该方法的有效性。此外，在2025年国际语音通信协会（Interspeech）举办的多语言对话语音语言建模挑战赛（MLC-SLM）中，MegaAIS团队运用此技术，在多语言语音识别任务（Track 1）中获得第4名，在语音分离与识别任务（Track 2）中夺冠，彰显了该方法的实践价值与广阔应用前景。

> The deep integration of large language models and automatic speech recognition systems has become a promising research direction with high practical value. To address the overfitting issue commonly observed in Low-Rank Adaptation (LoRA) during the supervised fine-tuning (SFT) stage, this work proposes an innovative training paradigm Iterative LoRA Training (ILT) in combination with an Iterative Pseudo Labeling strategy, effectively enhancing the theoretical upper bound of model performance. Based on Whisper-large-v3 and Qwen2-Audio, we conduct systematic experiments using a three-stage training process: Focus Training, Feed Back Training, and Fix Training. Experimental results demonstrate the effectiveness of the proposed method. Furthermore, the MegaAIS research team applied this technique in the Interspeech 2025 Multilingual Conversational Speech Language Modeling Challenge (MLC-SLM), achieving 4th in Track 1 (Multilingual ASR Task) and 1st place in Track 2 (Speech Separation and Recognition Task), showcasing the practical feasibility and strong application potential of our approach.

[Arxiv](https://arxiv.org/abs/2507.08477)