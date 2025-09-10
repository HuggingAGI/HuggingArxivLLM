# # 面向多模态对话系统的双知识增强两阶段推理器

发布时间：2025年09月09日

`LLM应用` `零售与电商`

> Dual Knowledge-Enhanced Two-Stage Reasoner for Multimodal Dialog Systems

# 摘要

> 文本响应生成是多模态面向任务对话系统的核心环节，其目标是基于多模态上下文生成恰当的文本响应。尽管现有研究已展现出显著进展，但仍存在两点局限：1）忽视非结构化评论知识；2）未充分发挥大型语言模型（LLMs）的潜力。鉴于此，我们计划借助LLMs充分利用双重知识（即结构化属性与非结构化评论知识），以提升多模态面向任务对话系统的文本响应生成质量。然而，该任务面临两大关键挑战，实现难度不小：1）动态知识类型选择；2）意图-响应解耦。为应对这些挑战，我们提出一种适配LLMs的多模态对话系统新型双重知识增强两阶段推理器（命名为DK2R）。具体而言，DK2R首先根据对话上下文从外部知识库中提取结构化属性和非结构化评论知识；随后利用LLM分析其生成的临时探测响应，评估各类知识的效用；此外，通过专门推理单独总结面向意图的关键线索，这些线索进而作为辅助信号，提升基于LLM的文本响应生成效果。在公共数据集上开展的大量实验验证了DK2R的优越性，我们已开源相关代码与参数。

> Textual response generation is pivotal for multimodal \mbox{task-oriented} dialog systems, which aims to generate proper textual responses based on the multimodal context. While existing efforts have demonstrated remarkable progress, there still exist the following limitations: 1) \textit{neglect of unstructured review knowledge} and 2) \textit{underutilization of large language models (LLMs)}. Inspired by this, we aim to fully utilize dual knowledge (\textit{i.e., } structured attribute and unstructured review knowledge) with LLMs to promote textual response generation in multimodal task-oriented dialog systems. However, this task is non-trivial due to two key challenges: 1) \textit{dynamic knowledge type selection} and 2) \textit{intention-response decoupling}. To address these challenges, we propose a novel dual knowledge-enhanced two-stage reasoner by adapting LLMs for multimodal dialog systems (named DK2R). To be specific, DK2R first extracts both structured attribute and unstructured review knowledge from external knowledge base given the dialog context. Thereafter, DK2R uses an LLM to evaluate each knowledge type's utility by analyzing LLM-generated provisional probe responses. Moreover, DK2R separately summarizes the intention-oriented key clues via dedicated reasoning, which are further used as auxiliary signals to enhance LLM-based textual response generation. Extensive experiments conducted on a public dataset verify the superiority of DK2R. We have released the codes and parameters.

[Arxiv](https://arxiv.org/abs/2509.07817)