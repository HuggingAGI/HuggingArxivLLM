# 基准测试：结合自动语音识别与大型语言模型模块的医疗诊断评估

发布时间：2025年02月18日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）在医疗领域中的实际应用，特别是结合自动语音识别（ASR）技术来处理医学通话录音，并生成专业的回应。研究的重点在于将LLM应用于医疗场景，优化其在不同环境下的表现，因此属于LLM应用类别。` `语音识别`

> Benchmarking Automatic Speech Recognition coupled LLM Modules for Medical Diagnostics

# 摘要

> 自然语言处理（NLP）和语音识别技术正在推动医疗领域的快速发展，通过实现高效、便捷且专业的患者支持，同时自动化繁琐的工作。本报告作为我的自研项目，重点分析了基于医学通话录音微调的模型，采用两阶段系统进行研究：首先是自动语音识别（ASR）进行语音转录，其次是大型语言模型（LLM）生成专业且上下文感知的回应。ASR在电话录音上进行了优化，能够准确转录通话中不同患者的语音，而LLM则负责将转录文本与医学诊断匹配。此外，我们引入了一种创新的音频预处理策略，以增强系统对不同录音环境的适应能力，通过增加噪声和剪辑等数据增强手段，使整个流程更加鲁棒，能够适应患者在不同麦克风和环境下进行通话或录音的情况。

> Natural Language Processing (NLP) and Voice Recognition agents are rapidly evolving healthcare by enabling efficient, accessible, and professional patient support while automating grunt work. This report serves as my self project wherein models finetuned on medical call recordings are analysed through a two-stage system: Automatic Speech Recognition (ASR) for speech transcription and a Large Language Model (LLM) for context-aware, professional responses. ASR, finetuned on phone call recordings provides generalised transcription of diverse patient speech over call, while the LLM matches transcribed text to medical diagnosis. A novel audio preprocessing strategy, is deployed to provide invariance to incoming recording/call data, laden with sufficient augmentation with noise/clipping to make the pipeline robust to the type of microphone and ambient conditions the patient might have while calling/recording.

[Arxiv](https://arxiv.org/abs/2502.13982)