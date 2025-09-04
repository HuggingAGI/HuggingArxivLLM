# 基于大型语言模型的助听器零样本非侵入式语音清晰度研究

发布时间：2025年09月03日

`LLM应用` `医疗健康`

> A Study on Zero-Shot Non-Intrusive Speech Intelligibility for Hearing Aids Using Large Language Models

# 摘要

> 本研究聚焦于利用大型语言模型（LLMs）实现助听器（HA）的零样本非侵入式语音评估。我们提出了GPT-Whisper-HA——这是基于LLMs的零样本非侵入式语音评估模型GPT-Whisper的扩展版本，专为助听器语音评估场景设计。该模型整合了MSBG听力损失与NAL-R模拟（基于个体听力图处理音频输入）、两个自动语音识别（ASR）模块（用于音频到文本的转换），以及GPT-4o（用于预测两个对应分数），最终通过分数平均得到估计结果。实验显示，相比GPT-Whisper，GPT-Whisper-HA的相对均方根误差（RMSE）降低了2.59%，证实了LLMs在零样本语音评估中预测助听器用户主观可懂度的潜力。

> This work focuses on zero-shot non-intrusive speech assessment for hearing aids (HA) using large language models (LLMs). Specifically, we introduce GPT-Whisper-HA, an extension of GPT-Whisper, a zero-shot non-intrusive speech assessment model based on LLMs. GPT-Whisper-HA is designed for speech assessment for HA, incorporating MSBG hearing loss and NAL-R simulations to process audio input based on each individual's audiogram, two automatic speech recognition (ASR) modules for audio-to-text representation, and GPT-4o to predict two corresponding scores, followed by score averaging for the final estimated score. Experimental results indicate that GPT-Whisper-HA achieves a 2.59% relative root mean square error (RMSE) improvement over GPT-Whisper, confirming the potential of LLMs for zero-shot speech assessment in predicting subjective intelligibility for HA users.

[Arxiv](https://arxiv.org/abs/2509.03021)