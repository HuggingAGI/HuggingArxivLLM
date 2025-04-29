# TD-EVAL: 结合回合级精度与对话级比较，重新审视任务导向型对话评估

发布时间：2025年04月28日

`Agent` `对话系统`

> TD-EVAL: Revisiting Task-Oriented Dialogue Evaluation by Combining Turn-Level Precision with Dialogue-Level Comparisons

# 摘要

> 任务导向对话 (TOD) 系统正经历一场由大型语言模型 (LLMs) 推动的革命，但现有评估方法尚未跟上其复杂性。传统自动指标虽能有效评估早期模块化系统，但仅关注对话层面，无法检测用户-代理交互中的关键中间错误。本文提出 TD-EVAL（回合和对话级评估），一个两步评估框架，将细粒度的回合级分析与整体的对话级比较相结合。在回合级，我们从对话连贯性、后端知识一致性和策略合规性三个维度评估响应。同时，我们设计了 TOD Agent Arena，通过配对比较提供对话级质量的衡量标准。实验表明，TD-EVAL 能有效识别传统指标遗漏的对话错误，并且与人类判断的契合度高于传统和基于 LLM 的指标。这些发现表明，TD-EVAL 引入了一种新的 TOD 系统评估范式，能够高效评估回合级和系统级，并为未来研究提供即插即用的框架。

> Task-oriented dialogue (TOD) systems are experiencing a revolution driven by Large Language Models (LLMs), yet the evaluation methodologies for these systems remain insufficient for their growing sophistication. While traditional automatic metrics effectively assessed earlier modular systems, they focus solely on the dialogue level and cannot detect critical intermediate errors that can arise during user-agent interactions. In this paper, we introduce TD-EVAL (Turn and Dialogue-level Evaluation), a two-step evaluation framework that unifies fine-grained turn-level analysis with holistic dialogue-level comparisons. At turn level, we evaluate each response along three TOD-specific dimensions: conversation cohesion, backend knowledge consistency, and policy compliance. Meanwhile, we design TOD Agent Arena that uses pairwise comparisons to provide a measure of dialogue-level quality. Through experiments on MultiWOZ 2.4 and τ-Bench, we demonstrate that TD-EVAL effectively identifies the conversational errors that conventional metrics miss. Furthermore, TD-EVAL exhibits better alignment with human judgments than traditional and LLM-based metrics. These findings demonstrate that TD-EVAL introduces a new paradigm for TOD system evaluation, efficiently assessing both turn and system levels with a plug-and-play framework for future research.

[Arxiv](https://arxiv.org/abs/2504.19982)