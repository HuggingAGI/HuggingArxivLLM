# JELLY: 基于LLMs的联合情感识别与上下文推理对话语音合成

发布时间：2025年01月08日

`LLM应用

理由：该论文主要讨论了如何通过微调大型语言模型（LLM）来改进对话语音合成（CSS），特别是通过情感识别和上下文推理来生成更自然的语音。这属于将LLM应用于特定任务（即对话语音合成）的范畴，因此归类为“LLM应用”。` `语音合成` `情感计算`

> JELLY: Joint Emotion Recognition and Context Reasoning with LLMs for Conversational Speech Synthesis

# 摘要

> 近年来，对话语音合成（CSS）的需求日益增长，旨在通过考虑对话上下文生成更自然的语音。为此，我们推出了JELLY，一个创新的CSS框架，它通过多个部分LoRA模块微调大型语言模型（LLM），结合情感识别和上下文推理，生成对话中情感适宜的语音。我们设计了情感感知的Q-former编码器，使LLM能够捕捉语音中的情感。该编码器利用情感语音数据集进行训练，将语音情感与文本对齐。随后，整个模型通过对话语音数据微调，推断情感上下文，生成对话中情感合适的语音。实验结果显示，JELLY在情感上下文建模方面表现卓越，能够合成与对话自然契合的语音，同时有效缓解了情感对话语音数据集的不足。

> Recently, there has been a growing demand for conversational speech synthesis (CSS) that generates more natural speech by considering the conversational context. To address this, we introduce JELLY, a novel CSS framework that integrates emotion recognition and context reasoning for generating appropriate speech in conversation by fine-tuning a large language model (LLM) with multiple partial LoRA modules. We propose an Emotion-aware Q-former encoder, which enables the LLM to perceive emotions in speech. The encoder is trained to align speech emotions with text, utilizing datasets of emotional speech. The entire model is then fine-tuned with conversational speech data to infer emotional context for generating emotionally appropriate speech in conversation. Our experimental results demonstrate that JELLY excels in emotional context modeling, synthesizing speech that naturally aligns with conversation, while mitigating the scarcity of emotional conversational speech datasets.

[Arxiv](https://arxiv.org/abs/2501.04904)