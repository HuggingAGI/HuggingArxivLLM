# 超越分类：利用多任务AudioLLMs探索语音情感推理

发布时间：2025年06月07日

`LLM应用

摘要讨论了音频大语言模型在情感识别中的应用，提出了一种新策略和框架，以提升情感推理能力，属于应用层面的研究。` `语音处理`

> Beyond Classification: Towards Speech Emotion Reasoning with Multitask AudioLLMs

# 摘要

> 音频大语言模型（AudioLLMs）在语音识别和翻译等语义任务中表现优异，但在情感等副语言提示的建模方面仍存在局限。现有方法通常将情感理解视为分类任务，难以深入揭示预测背后的推理逻辑。本研究提出了一种基于情感推理的新策略，通过利用音频大语言模型的生成能力，生成语义对齐且有依据的解释来提升情感识别效果。为支持多任务音频大语言模型中的情感推理，我们提出了一种统一框架，结合推理增强的数据监督、双编码器架构和任务交替训练。这种方法不仅使音频大语言模型能够有效学习不同任务，还显著提升了情感推理能力。实验结果表明，与现有方法相比，我们的方法在IEMOCAP和MELD数据集上不仅提高了情感预测的准确性，还显著增强了生成响应的连贯性和证据依据性。

> Audio Large Language Models (AudioLLMs) have achieved strong results in semantic tasks like speech recognition and translation, but remain limited in modeling paralinguistic cues such as emotion. Existing approaches often treat emotion understanding as a classification problem, offering little insight into the underlying rationale behind predictions. In this work, we explore emotion reasoning, a strategy that leverages the generative capabilities of AudioLLMs to enhance emotion recognition by producing semantically aligned, evidence-grounded explanations. To support this in multitask AudioLLMs, we introduce a unified framework combining reasoning-augmented data supervision, dual-encoder architecture, and task-alternating training. This approach enables AudioLLMs to effectively learn different tasks while incorporating emotional reasoning. Experiments on IEMOCAP and MELD show that our approach not only improves emotion prediction accuracy but also enhances the coherence and evidential grounding of the generated responses.

[Arxiv](https://arxiv.org/abs/2506.06820)