# 从“足够”到“反思”：强化引导的思考质量评估在检索增强的推理能力中的应用（针对大型语言模型）

发布时间：2025年07月30日

`RAG` `问答系统`

> From Sufficiency to Reflection: Reinforcement-Guided Thinking Quality in Retrieval-Augmented Reasoning for LLMs

# 摘要

> 基于强化学习的检索增强生成（RAG）方法能够提升大型语言模型（LLMs）的推理能力。然而，大多数现有方法仅依赖最终答案奖励，忽视了中间推理质量。本文分析了现有的RAG推理模型，并识别出三种主要的失败模式：（1）信息不足，即模型未能检索到足够的支持信息；（2）推理错误，在信息充足的情况下仍然出现逻辑或内容层面的缺陷；（3）答案-推理不一致，即有效的推理链路却导致了与之不匹配的最终答案。

我们提出了TIRESRAG-R1，一个采用"思考-检索-反思"流程和多维奖励系统的新型框架，旨在提升推理能力和稳定性。TIRESRAG-R1引入了：（1）充分性奖励，以鼓励全面检索；（2）推理质量奖励，用于评估推理链路的合理性和准确性；（3）反思奖励，用于检测并修正错误。此外，该框架还采用了难度感知的重新加权策略和训练样本过滤机制，以提升在复杂任务上的表现。

在四个多跳问答数据集上的实验表明，TIRESRAG-R1优于现有RAG方法，并且能够很好地泛化到单跳任务。代码和数据可在以下链接获取：https://github.com/probe2/TIRESRAG-R1。


> Reinforcement learning-based retrieval-augmented generation (RAG) methods enhance the reasoning abilities of large language models (LLMs). However, most rely only on final-answer rewards, overlooking intermediate reasoning quality. This paper analyzes existing RAG reasoning models and identifies three main failure patterns: (1) information insufficiency, meaning the model fails to retrieve adequate support; (2) faulty reasoning, where logical or content-level flaws appear despite sufficient information; and (3) answer-reasoning inconsistency, where a valid reasoning chain leads to a mismatched final answer. We propose TIRESRAG-R1, a novel framework using a think-retrieve-reflect process and a multi-dimensional reward system to improve reasoning and stability. TIRESRAG-R1 introduces: (1) a sufficiency reward to encourage thorough retrieval; (2) a reasoning quality reward to assess the rationality and accuracy of the reasoning chain; and (3) a reflection reward to detect and revise errors. It also employs a difficulty-aware reweighting strategy and training sample filtering to boost performance on complex tasks. Experiments on four multi-hop QA datasets show that TIRESRAG-R1 outperforms prior RAG methods and generalizes well to single-hop tasks. The code and data are available at: https://github.com/probe2/TIRESRAG-R1.

[Arxiv](https://arxiv.org/abs/2507.22716)