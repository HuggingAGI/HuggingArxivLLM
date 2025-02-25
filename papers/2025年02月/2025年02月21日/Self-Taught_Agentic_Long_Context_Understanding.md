# # 自我学习智能体实现长上下文理解

发布时间：2025年02月21日

`LLM应用` `问答系统`

> Self-Taught Agentic Long Context Understanding

# 摘要

> 回答复杂且长上下文的问题一直是大型语言模型 (LLMs) 的一大挑战，因为这需要有效的问答澄清和上下文检索。我们提出了一种名为“智能长上下文理解” (AgenticLU) 的框架，通过在智能体工作流程中整合目标自我澄清与上下文接地，提升 LLM 对此类查询的理解能力。AgenticLU 的核心是“澄清链” (Chain-of-Clarifications, CoC)，其中模型通过自动生成的澄清问题及其对应的上下文接地来逐步细化理解。通过将推理过程扩展为树搜索，每个节点代表一个 CoC 步骤，我们在 NarrativeQA 数据集上实现了 97.8% 的答案召回率，搜索深度为三，分支因子为八。为了将这种搜索过程的高成本分摊到训练中，我们利用 CoC 工作流程中每一步获得的偏好对，并进行两阶段模型微调：(1) 监督微调以学习有效的分解策略，以及 (2) 直接偏好优化以提升推理质量。这使得 AgenticLU 模型能够在单次推理过程中高效地生成澄清问题并检索相关上下文。在涵盖七个长上下文任务的广泛实验中，AgenticLU 显著超越了现有的最佳提示方法和专门设计的长上下文 LLM，实现了稳健的多跳推理，同时在上下文长度增加时保持了性能的一致性。

> Answering complex, long-context questions remains a major challenge for large language models (LLMs) as it requires effective question clarifications and context retrieval. We propose Agentic Long-Context Understanding (AgenticLU), a framework designed to enhance an LLM's understanding of such queries by integrating targeted self-clarification with contextual grounding within an agentic workflow. At the core of AgenticLU is Chain-of-Clarifications (CoC), where models refine their understanding through self-generated clarification questions and corresponding contextual groundings. By scaling inference as a tree search where each node represents a CoC step, we achieve 97.8% answer recall on NarrativeQA with a search depth of up to three and a branching factor of eight. To amortize the high cost of this search process to training, we leverage the preference pairs for each step obtained by the CoC workflow and perform two-stage model finetuning: (1) supervised finetuning to learn effective decomposition strategies, and (2) direct preference optimization to enhance reasoning quality. This enables AgenticLU models to generate clarifications and retrieve relevant context effectively and efficiently in a single inference pass. Extensive experiments across seven long-context tasks demonstrate that AgenticLU significantly outperforms state-of-the-art prompting methods and specialized long-context LLMs, achieving robust multi-hop reasoning while sustaining consistent performance as context length grows.

[Arxiv](https://arxiv.org/abs/2502.15920)