# 用于与任务无关的语音 LLM 预训练的对比学习

发布时间：2024年12月20日

`LLM应用` `语音处理`

> Contrastive Learning for Task-Independent SpeechLLM-Pretraining

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域表现卓越，然而要让这些 LLMs 高效适配语音处理任务并非轻而易举。直接进行特定任务的微调会受到过拟合风险、数据需求和计算成本的制约。为应对此类挑战，我们提出了一种可扩展的两阶段训练方式：（1）先进行与任务无关的语音预训练阶段，运用对比学习在所有层面对文本和语音的表征进行对齐；（2）接着是只需少量数据的特定任务微调阶段。该方法优于传统的 ASR 预训练，能让模型超越专门用于语音翻译和问答的模型，且仅用 10%的特定任务数据进行训练。

> Large language models (LLMs) excel in natural language processing but adapting these LLMs to speech processing tasks efficiently is not straightforward. Direct task-specific fine-tuning is limited by overfitting risks, data requirements, and computational costs. To address these challenges, we propose a scalable, two-stage training approach: (1) A task-independent speech pretraining stage using contrastive learning to align text and speech representations over all layers, followed by (2) a task-specific fine-tuning stage requiring minimal data. This approach outperforms traditional ASR pretraining and enables the model to surpass models specialized on speech translation and question answering while being trained on only 10% of the task-specific data.

[Arxiv](https://arxiv.org/abs/2412.15712)