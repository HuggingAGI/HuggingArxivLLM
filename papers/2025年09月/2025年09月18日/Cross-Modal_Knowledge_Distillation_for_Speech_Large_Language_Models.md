# 面向语音大语言模型的跨模态知识蒸馏

发布时间：2025年09月18日

`LLM应用` `媒体与娱乐`

> Cross-Modal Knowledge Distillation for Speech Large Language Models

# 摘要

> 本研究首次对语音大型语言模型中的灾难性遗忘与模态不等价性展开系统性评估，结果显示：引入语音能力可能会削弱模型的知识与推理能力——即便输入仍是文本形式；而当使用语音查询时，性能会进一步下降。为应对这些挑战，我们提出一种跨模态知识蒸馏框架，该框架同时利用文本到文本和语音到文本两种通道，将知识从基于文本的教师模型迁移至语音大型语言模型。在对话和音频理解任务上的大量实验证实，我们的方法在保留文本知识、改善跨模态对齐以及增强基于语音交互的推理能力方面均有效。

> In this work, we present the first systematic evaluation of catastrophic forgetting and modality inequivalence in speech large language models, showing that introducing speech capabilities can degrade knowledge and reasoning even when inputs remain textual, and performance further decreases with spoken queries. To address these challenges, we propose a cross-modal knowledge distillation framework that leverages both text-to-text and speech-to-text channels to transfer knowledge from a text-based teacher model to a speech LLM. Extensive experiments on dialogue and audio understanding tasks validate the effectiveness of our approach in preserving textual knowledge, improving cross-modal alignment, and enhancing reasoning in speech-based interactions.

[Arxiv](https://arxiv.org/abs/2509.14930)