# # FiSMiness：基于有限状态机的情感支持对话新范式
FiSMiness 是一种基于有限状态机（FSM）的情感支持对话新范式。它通过 FSM 的状态转移机制，为情感支持对话设计了一种结构化的方法论。

发布时间：2025年04月16日

`LLM应用

摘要中讨论了如何将大型语言模型（LLMs）应用于情感支持对话（ESC），并提出了一种基于有限状态机（FSM）的框架FiSMiness。该框架旨在改善LLMs在ESC中的表现，属于将LLMs应用于具体任务的范畴，因此归类为LLM应用。` `人工智能`

> FiSMiness: A Finite State Machine Based Paradigm for Emotional Support Conversations

# 摘要

> 情感支持对话（ESC）致力于通过有效沟通缓解个体情绪困扰。尽管大型语言模型（LLMs）在ESC领域取得了显著进展，但多数研究未能从状态模型的角度构建框架，导致长期满意度不佳。为解决这一问题，我们基于有限状态机（FSM）提出名为FiSMiness的框架。该框架使单个LLM能够在ESC中自主规划，并在每次对话轮次中实时推理求助者情绪、支持策略及最终回应。实验结果表明，FiSMiness在ESC数据集上超越了多种基线方法，包括直接推理、自我优化、思维链、微调及外部辅助方法，甚至优于那些参数量更大的模型。

> Emotional support conversation (ESC) aims to alleviate the emotional distress of individuals through effective conversations. Although large language models (LLMs) have obtained remarkable progress on ESC, most of these studies might not define the diagram from the state model perspective, therefore providing a suboptimal solution for long-term satisfaction. To address such an issue, we leverage the Finite State Machine (FSM) on LLMs, and propose a framework called FiSMiness. Our framework allows a single LLM to bootstrap the planning during ESC, and self-reason the seeker's emotion, support strategy and the final response upon each conversational turn. Substantial experiments on ESC datasets suggest that FiSMiness outperforms many baselines, including direct inference, self-refine, chain of thought, finetuning, and external-assisted methods, even those with many more parameters.

[Arxiv](https://arxiv.org/abs/2504.11837)