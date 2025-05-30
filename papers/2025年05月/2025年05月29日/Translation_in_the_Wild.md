# # 真实世界的翻译

发布时间：2025年05月29日

`LLM理论` `机器翻译`

> Translation in the Wild

# 摘要

> 大型语言模型（LLMs）在翻译等任务中表现出色，尤其在零样本和少样本设置下，其性能与许多语言对的专用神经机器翻译模型相当。然而，与专注于翻译任务的神经机器翻译模型不同，LLMs 并未在任何翻译相关的训练目标上进行训练。那么，它们出色的翻译能力背后是什么原因？这些能力是否源于训练数据中的“偶然双语现象”（Briakou et al. 2023）？指令微调是否对其有所帮助？LLMs 是否能够识别并利用来自互联网不同角落的语义相同或相似的单语内容，尽管这些内容可能无法同时容纳在一个上下文窗口中？本文基于近期研究和不断增长的用户体验，对这一问题进行了一些思考。我的工作假设是，LLMs 的翻译能力源自两种不同类型的预训练数据，这些数据可能以不同方式被模型内化。本文探讨了如何通过实证测试“双重性”假设，并讨论了这一假设对重新概念化深度学习时代的人类与机器翻译的启示。

> Large Language Models (LLMs) excel in translation among other things, demonstrating competitive performance for many language pairs in zero- and few-shot settings. But unlike dedicated neural machine translation models, LLMs are not trained on any translation-related objective. What explains their remarkable translation abilities? Are these abilities grounded in "incidental bilingualism" (Briakou et al. 2023) in training data? Does instruction tuning contribute to it? Are LLMs capable of aligning and leveraging semantically identical or similar monolingual contents from different corners of the internet that are unlikely to fit in a single context window? I offer some reflections on this topic, informed by recent studies and growing user experience. My working hypothesis is that LLMs' translation abilities originate in two different types of pre-training data that may be internalized by the models in different ways. I discuss the prospects for testing the "duality" hypothesis empirically and its implications for reconceptualizing translation, human and machine, in the age of deep learning.

[Arxiv](https://arxiv.org/abs/2505.23548)