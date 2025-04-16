# # **ReZero：再试一次，助力大语言模型搜索能力升级**

发布时间：2025年04月15日

`RAG` `信息检索`

> ReZero: Enhancing LLM search ability by trying one-more-time

# 摘要

> 检索增强生成（RAG）在知识密集型任务上显著提升了大型语言模型（LLM）的性能，但其效果高度依赖于初始搜索查询的质量。现有方法通常采用强化学习（RL），主要关注查询构建或结果推理，却忽视了在搜索失败后鼓励重试的重要性。为此，我们提出ReZero（Retry-Zero），一种全新的RL框架，通过直接奖励在初次搜索失败后重新尝试查询的行为，激励LLM探索更多替代方案，而非过早终止。实验结果表明，ReZero在准确率上实现了46.88%的显著提升，远超25%的基线水平。通过奖励坚持不懈的精神，ReZero在复杂信息检索场景中显著增强了LLM的鲁棒性，尤其是在初始查询可能无法满足需求的情况下。

> Retrieval-Augmented Generation (RAG) improves Large Language Model (LLM) performance on knowledge-intensive tasks but depends heavily on initial search query quality. Current methods, often using Reinforcement Learning (RL), typically focus on query formulation or reasoning over results, without explicitly encouraging persistence after a failed search. We introduce ReZero (Retry-Zero), a novel RL framework that directly rewards the act of retrying a search query following an initial unsuccessful attempt. This incentivizes the LLM to explore alternative queries rather than prematurely halting. ReZero demonstrates significant improvement, achieving 46.88% accuracy compared to a 25% baseline. By rewarding persistence, ReZero enhances LLM robustness in complex information-seeking scenarios where initial queries may prove insufficient.

[Arxiv](https://arxiv.org/abs/2504.11001)