# 面向高效稳健多轮对话的状态更新提示策略

发布时间：2025年09月22日

`LLM应用` `基础理论`

> A State-Update Prompting Strategy for Efficient and Robust Multi-turn Dialogue

# 摘要

> 大型语言模型（LLMs）在长程多轮对话中常受困于信息遗忘与效率不足。为此，我们提出一种免训练提示工程方法——状态更新多轮对话策略。该策略通过“状态重构”与“历史提醒”机制，实现对话历史的高效管理。该策略在多个多跳问答数据集上均展现出色性能：例如在HotpotQA数据集上，核心信息过滤得分提升32.6%，下游问答得分随之提高14.1%，推理时间缩短73.1%，令牌消耗减少59.4%。消融实验验证了这两个组件的核心作用。本研究为优化长程交互中的LLMs提供了有效方案，也为构建更稳健的智能体带来新启示。

> Large Language Models (LLMs) struggle with information forgetting and inefficiency in long-horizon, multi-turn dialogues. To address this, we propose a training-free prompt engineering method, the State-Update Multi-turn Dialogue Strategy. It utilizes "State Reconstruction" and "History Remind" mechanisms to effectively manage dialogue history. Our strategy shows strong performance across multiple multi-hop QA datasets. For instance, on the HotpotQA dataset, it improves the core information filtering score by 32.6%, leading to a 14.1% increase in the downstream QA score, while also reducing inference time by 73.1% and token consumption by 59.4%. Ablation studies confirm the pivotal roles of both components. Our work offers an effective solution for optimizing LLMs in long-range interactions, providing new insights for developing more robust Agents.

[Arxiv](https://arxiv.org/abs/2509.17766)