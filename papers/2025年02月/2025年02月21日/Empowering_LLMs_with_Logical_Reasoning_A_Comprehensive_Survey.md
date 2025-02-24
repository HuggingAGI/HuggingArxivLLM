# 逻辑推理赋能大型语言模型：全面综述

发布时间：2025年02月21日

`LLM理论` `逻辑推理`

> Empowering LLMs with Logical Reasoning: A Comprehensive Survey

# 摘要

> 大型语言模型（LLMs）在自然语言任务中表现出色，但在逻辑推理方面仍存在显著挑战。本文将这些挑战归纳为两个主要方面：（1）逻辑问答，LLMs在处理复杂推理问题时常常表现不佳；（2）逻辑一致性，LLMs容易在回答中出现矛盾。例如，Macaw模型对“喜鹊是鸟吗？”和“鸟有翅膀吗？”回答“是”，但对“喜鹊有翅膀吗？”却回答“否”。为推动这一研究领域，我们系统梳理了前沿方法，提出了详细分类。针对复杂逻辑问题，现有方法可按对外部求解器、提示、预训练和微调的依赖进行分类。为避免矛盾，我们探讨了蕴含、否定、传递性、事实一致性等概念及其解决方案。此外，我们还总结了常用数据集和评估指标，并展望了扩展模态逻辑和开发多逻辑一致性算法等研究方向。


> Large language models (LLMs) have achieved remarkable successes on various natural language tasks. However, recent studies have found that there are still significant challenges to the logical reasoning abilities of LLMs. This paper summarizes and categorizes the main challenges into two aspects: (1) Logical question answering, LLMs often fail to generate the correct answer within complex logical problem which requires sophisticated deductive, inductive or abductive reasoning given a collection of premises and constrains. (2) Logical consistency, LLMs are prone to producing responses contradicting themselves across different questions. For example, a state-of-the-art Macaw question-answering LLM answers Yes to both questions Is a magpie a bird? and Does a bird have wings? but answers No to Does a magpie have wings?. To facilitate this research direction, we comprehensively investigate the most cutting-edge methods and propose detailed taxonomies of these methods. Specifically, to accurately answer complex logic questions, previous methods can be categorized based on reliance on external solvers, prompts, pretraining, and fine-tuning. To avoid logical contradictions, we discuss concepts and solutions of various logical consistencies, including implication, negation, transitivity, factuality consistency, and their composites. In addition, we review commonly used benchmark datasets and evaluation metrics, and discuss promising research directions, such as extensions to modal logic to account for uncertainty, and efficient algorithms satisfying multiple logical consistencies simultaneously.

[Arxiv](https://arxiv.org/abs/2502.15652)