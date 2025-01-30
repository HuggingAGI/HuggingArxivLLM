# NUS-Emo 在 SemEval-2024 任务 3 中：通过指令调优 LLM 实现对话中的多模态情感-原因分析

发布时间：2024年08月22日

`LLM应用` `情感分析`

> NUS-Emo at SemEval-2024 Task 3: Instruction-Tuning LLM for Multimodal Emotion-Cause Analysis in Conversations

# 摘要

> 本文介绍了为SemEval-2024任务3开发的系统架构：对话中的多模态情感-原因分析。我们专注于子任务2——带有情感类别的多模态情感-原因对提取（MECPE-Cat），并构建了一个双组件系统来应对其独特挑战。任务被分为两个子任务：对话中的情感识别（ERC）和情感-原因对提取（ECPE）。我们利用大型语言模型（LLMs）的强大能力，这些模型在各类自然语言处理任务中表现卓越。特别地，我们设计了一种情感-原因感知的指令调优方法，以增强LLMs对情感及其因果关系的感知。该方法帮助我们成功应对MECPE-Cat的复杂性，取得了加权平均34.71%的F1分数，并在排行榜上位列第二。实验代码和元数据已公开。

> This paper describes the architecture of our system developed for Task 3 of SemEval-2024: Multimodal Emotion-Cause Analysis in Conversations. Our project targets the challenges of subtask 2, dedicated to Multimodal Emotion-Cause Pair Extraction with Emotion Category (MECPE-Cat), and constructs a dual-component system tailored to the unique challenges of this task. We divide the task into two subtasks: emotion recognition in conversation (ERC) and emotion-cause pair extraction (ECPE). To address these subtasks, we capitalize on the abilities of Large Language Models (LLMs), which have consistently demonstrated state-of-the-art performance across various natural language processing tasks and domains. Most importantly, we design an approach of emotion-cause-aware instruction-tuning for LLMs, to enhance the perception of the emotions with their corresponding causal rationales. Our method enables us to adeptly navigate the complexities of MECPE-Cat, achieving a weighted average 34.71% F1 score of the task, and securing the 2nd rank on the leaderboard. The code and metadata to reproduce our experiments are all made publicly available.

[Arxiv](https://arxiv.org/abs/2501.17261)