# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月07日

`LLM理论` `人工智能`

> Not All Data Are Unlearned Equally

# 摘要

> 机器遗忘（Machine unlearning）旨在从训练好的模型中移除特定数据点所教授的知识。在大型语言模型（LLMs）领域，遗忘近期备受关注，尤其是为隐私起见，移除模型中与命名实体相关的信息。尽管多种遗忘方法已被提出，但现有方法大多将待遗忘的所有数据同等对待——例如，遗忘“蒙特利尔是加拿大的城市”与遗忘“本文第一作者的电话号码”被视为同等重要的任务。本研究揭示，这种“数据一律平等”的假设并不适用于LLM的遗忘机制。我们深入探究了遗忘效果与预训练数据中目标知识频率之间的关系，发现频率显著影响遗忘难度——知识越常见，遗忘越困难。此外，我们发现基于概率与生成的遗忘评估存在不一致，并且这一问题随着模型规模的扩大而愈发严重。总体而言，我们的实验结果凸显了改进评估实践的必要性，并呼吁开发新的LLM遗忘方法，这些方法需充分考虑模型的训练数据。

> Machine unlearning is concerned with the task of removing knowledge learned from particular data points from a trained model. In the context of large language models (LLMs), unlearning has recently received increased attention, particularly for removing knowledge about named entities from models for privacy purposes. While various approaches have been proposed to address the unlearning problem, most existing approaches treat all data points to be unlearned equally, i.e., unlearning that Montreal is a city in Canada is treated exactly the same as unlearning the phone number of the first author of this paper. In this work, we show that this all data is equal assumption does not hold for LLM unlearning. We study how the success of unlearning depends on the frequency of the knowledge we want to unlearn in the pre-training data of a model and find that frequency strongly affects unlearning, i.e., more frequent knowledge is harder to unlearn. Additionally, we uncover a misalignment between probability and generation-based evaluations of unlearning and show that this problem worsens as models become larger. Overall, our experiments highlight the need for better evaluation practices and novel methods for LLM unlearning that take the training data of models into account.

[Arxiv](https://arxiv.org/abs/2504.05058)