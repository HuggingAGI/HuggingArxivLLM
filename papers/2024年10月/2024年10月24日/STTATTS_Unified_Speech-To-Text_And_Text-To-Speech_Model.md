# STTATTS: 语音转文本与文本转语音的统一模型

发布时间：2024年10月24日

`其他

解释：这篇论文主要讨论了语音识别（ASR）和语音合成（TTS）模型的联合训练方法，通过多任务学习和参数共享来提高效率。虽然涉及到了模型训练和优化，但并没有直接涉及到大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等概念。因此，将其分类为“其他”更为合适。` `语音识别` `语音合成`

> STTATTS: Unified Speech-To-Text And Text-To-Speech Model

# 摘要

> 语音识别和语音合成模型通常独立训练，各自拥有不同的学习目标、训练数据和模型参数，形成两个独立的大型网络。我们提出了一种参数高效的方法，通过多任务学习目标和共享参数联合训练ASR和TTS。评估结果显示，多任务模型的性能与单独训练的模型相当，同时显著降低了计算和内存成本（两个任务的总参数数量减少了约50%）。我们以英语（资源丰富）和阿拉伯语（资源匮乏，TTS数据不足）进行实验。模型使用公开数据训练，训练代码和模型检查点均已开源，供进一步研究使用。

> Speech recognition and speech synthesis models are typically trained separately, each with its own set of learning objectives, training data, and model parameters, resulting in two distinct large networks. We propose a parameter-efficient approach to learning ASR and TTS jointly via a multi-task learning objective and shared parameters. Our evaluation demonstrates that the performance of our multi-task model is comparable to that of individually trained models while significantly saving computational and memory costs ($\sim$50\% reduction in the total number of parameters required for the two tasks combined). We experiment with English as a resource-rich language, and Arabic as a relatively low-resource language due to shortage of TTS data. Our models are trained with publicly available data, and both the training code and model checkpoints are openly available for further research.

[Arxiv](https://arxiv.org/abs/2410.18607)