# EchoX：致力于通过回声训练弥合语音到语音LLM的声学-语义差距

发布时间：2025年09月11日

`LLM应用` `基础理论`

> EchoX: Towards Mitigating Acoustic-Semantic Gap via Echo Training for Speech-to-Speech LLMs

# 摘要

> 语音到语音大型语言模型（SLLMs）日益受到关注。作为文本大型语言模型（LLMs）的衍生模型，SLLMs 常出现知识与推理能力退化的问题。我们推测，这一局限源于当前 SLLMs 训练范式未能弥合特征表示空间中的声学-语义鸿沟。为解决此问题，我们提出 EchoX，它借助语义表示动态生成语音训练目标。该方法融合声学与语义学习，使 EchoX 作为语音 LLM 仍能保留强大的推理能力。实验结果显示，仅用约六千小时训练数据的 EchoX，就在多个知识问答基准测试中取得了优异性能。项目地址：https://github.com/FreedomIntelligence/EchoX。

> Speech-to-speech large language models (SLLMs) are attracting increasing attention. Derived from text-based large language models (LLMs), SLLMs often exhibit degradation in knowledge and reasoning capabilities. We hypothesize that this limitation arises because current training paradigms for SLLMs fail to bridge the acoustic-semantic gap in the feature representation space. To address this issue, we propose EchoX, which leverages semantic representations and dynamically generates speech training targets. This approach integrates both acoustic and semantic learning, enabling EchoX to preserve strong reasoning abilities as a speech LLM. Experimental results demonstrate that EchoX, with about six thousand hours of training data, achieves advanced performance on multiple knowledge-based question-answering benchmarks. The project is available at https://github.com/FreedomIntelligence/EchoX.

[Arxiv](https://arxiv.org/abs/2509.09174)