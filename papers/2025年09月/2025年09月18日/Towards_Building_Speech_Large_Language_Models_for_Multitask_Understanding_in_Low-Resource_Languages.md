# 迈向构建面向低资源语言多任务理解的语音大型语言模型

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Towards Building Speech Large Language Models for Multitask Understanding in Low-Resource Languages

# 摘要

> 基于语音编码器、适配器和大型语言模型（LLMs）构建的语音大语言模型（SLLMs），在英语、中文等高资源语言中展现出卓越的多任务理解能力。但在泰语这类低资源语言中，其性能却大打折扣。这一短板主要源于三方面：（1）主流语音编码器（如Whisper系列）在低资源语言中表现拉垮，且无法支持更广泛的口语理解任务；（2）基于ASR的对齐范式需训练整个SLLM，计算成本极高；（3）低资源语言的语音-文本配对数据十分匮乏。为破解泰语这一低资源语言的困境，我们推出了XLSR-Thai——首个泰语自监督学习（SSL）语音编码器。它通过在36,000小时泰语语音数据上持续训练标准SSL XLSR模型而得。此外，我们提出U-Align方法，这是一种比传统ASR对齐方式资源效率更高、多任务适配性更强的语音-文本对齐方案。最后，我们构建了Thai-SUP管道，可从高资源语言生成泰语口语理解数据，进而打造出首个超1,000小时的泰语口语理解数据集。多项实验证实，我们的方法能有效构建泰语多任务理解SLLM。目前，XLSR-Thai与Thai-SUP已开源，以期助力后续研究。

> Speech large language models (SLLMs) built on speech encoders, adapters, and LLMs demonstrate remarkable multitask understanding performance in high-resource languages such as English and Chinese. However, their effectiveness substantially degrades in low-resource languages such as Thai. This limitation arises from three factors: (1) existing commonly used speech encoders, like the Whisper family, underperform in low-resource languages and lack support for broader spoken language understanding tasks; (2) the ASR-based alignment paradigm requires training the entire SLLM, leading to high computational cost; (3) paired speech-text data in low-resource languages is scarce. To overcome these challenges in the low-resource language Thai, we introduce XLSR-Thai, the first self-supervised learning (SSL) speech encoder for Thai. It is obtained by continuously training the standard SSL XLSR model on 36,000 hours of Thai speech data. Furthermore, we propose U-Align, a speech-text alignment method that is more resource-efficient and multitask-effective than typical ASR-based alignment. Finally, we present Thai-SUP, a pipeline for generating Thai spoken language understanding data from high-resource languages, yielding the first Thai spoken language understanding dataset of over 1,000 hours. Multiple experiments demonstrate the effectiveness of our methods in building a Thai multitask-understanding SLLM. We open-source XLSR-Thai and Thai-SUP to facilitate future research.

[Arxiv](https://arxiv.org/abs/2509.14804)