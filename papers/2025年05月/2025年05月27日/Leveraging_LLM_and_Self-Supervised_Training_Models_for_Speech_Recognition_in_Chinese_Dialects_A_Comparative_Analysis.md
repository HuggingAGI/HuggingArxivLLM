# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月27日

`LLM应用` `语音识别` `方言识别`

> Leveraging LLM and Self-Supervised Training Models for Speech Recognition in Chinese Dialects: A Comparative Analysis

# 摘要

> 大规模训练语料库显著提升了语音识别（ASR）模型的性能。然而，中文口音和方言的识别仍然是大多数ASR模型的难题，主要由于数据资源相对匮乏。近期，自监督学习的突破表明，结合自监督预训练与大型语言模型（LLM）可以在低资源场景下有效提升ASR性能。我们致力于研究这一范式在中文方言识别中的有效性。具体而言，我们基于30万小时无标签方言和口音语音数据预训练了一个Data2vec2模型，并在4万小时的监督数据集上进行对齐训练。随后，我们系统地考察了不同投影器和LLM对普通话、方言和口音语音识别性能的影响。我们的方法在多个方言数据集上取得了最优结果，包括Kespeech。为了促进可重复研究，我们将开源我们的工作。

> Large-scale training corpora have significantly improved the performance of ASR models. Unfortunately, due to the relative scarcity of data, Chinese accents and dialects remain a challenge for most ASR models. Recent advancements in self-supervised learning have shown that self-supervised pre- training, combined with large language models (LLM), can effectively enhance ASR performance in low-resource scenarios. We aim to investigate the effectiveness of this paradigm for Chinese dialects. Specifically, we pre-train a Data2vec2 model on 300,000 hours of unlabeled dialect and accented speech data and do alignment training on a supervised dataset of 40,000 hours. Then, we systematically examine the impact of various projectors and LLMs on Mandarin, dialect, and accented speech recognition performance under this paradigm. Our method achieved SOTA results on multiple dialect datasets, including Kespeech. We will open-source our work to promote reproducible research

[Arxiv](https://arxiv.org/abs/2505.21138)