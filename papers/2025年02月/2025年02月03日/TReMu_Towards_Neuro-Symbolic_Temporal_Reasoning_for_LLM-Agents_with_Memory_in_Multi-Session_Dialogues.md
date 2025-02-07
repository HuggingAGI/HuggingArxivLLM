# TReMu: 为具备记忆的LLM-智能体在多轮对话中实现神经符号时序推理

发布时间：2025年02月03日

`Agent

理由：这篇论文主要讨论了在多会话对话中提升LLM代理的时间推理能力，提出了TReMu框架，并通过时间线摘要和神经符号时间推理来增强LLM代理的性能。论文的核心是围绕如何改进LLM代理在多会话对话中的表现，因此应归类为Agent。` `对话系统` `时间推理`

> TReMu: Towards Neuro-Symbolic Temporal Reasoning for LLM-Agents with Memory in Multi-Session Dialogues

# 摘要

> # 多会话对话中的时间推理
多会话对话中的时间推理是一个重要但尚未充分研究的挑战。为了填补这一空白，我们提出了一个新的时间推理评估任务，并通过增强LoCoMo对话和创建多选QA来构建新基准。此外，我们推出了TReMu框架，旨在提升LLM代理在多会话对话中的时间推理能力。该框架通过时间线摘要实现	extit{时间感知记忆}，总结每个对话会话中的事件及其推断日期，生成可检索的记忆。同时，我们引入了	extit{神经符号时间推理}，LLM生成Python代码进行时间计算并选择答案。实验表明，我们的基准具有挑战性，且TReMu框架显著提升了时间推理性能，从标准提示下GPT-4o的29.83提升至我们方法下的77.67，有效解决了多会话对话中的时间推理问题。

> Temporal reasoning in multi-session dialogues presents a significant challenge which has been under-studied in previous temporal reasoning benchmarks. To bridge this gap, we propose a new evaluation task for temporal reasoning in multi-session dialogues and introduce an approach to construct a new benchmark by augmenting dialogues from LoCoMo and creating multi-choice QAs. Furthermore, we present TReMu, a new framework aimed at enhancing the temporal reasoning capabilities of LLM-agents in this context. Specifically, the framework employs \textit{time-aware memorization} through timeline summarization, generating retrievable memory by summarizing events in each dialogue session with their inferred dates. Additionally, we integrate \textit{neuro-symbolic temporal reasoning}, where LLMs generate Python code to perform temporal calculations and select answers. Experimental evaluations on popular LLMs demonstrate that our benchmark is challenging, and the proposed framework significantly improves temporal reasoning performance compared to baseline methods, raising from 29.83 on GPT-4o via standard prompting to 77.67 via our approach and highlighting its effectiveness in addressing temporal reasoning in multi-session dialogues.

[Arxiv](https://arxiv.org/abs/2502.01630)