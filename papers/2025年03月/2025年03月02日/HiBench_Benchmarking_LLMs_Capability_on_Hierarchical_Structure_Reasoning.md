# HiBench：评测大型语言模型（LLMs）在层次结构推理能力

发布时间：2025年03月02日

`LLM理论

摘要讨论了大型语言模型的结构推理能力，特别是层级结构推理，并提出了一种新的评估框架HiBench。这属于对模型能力的理论分析和改进，因此归类为LLM理论。` `人工智能` `数据科学`

> HiBench: Benchmarking LLMs Capability on Hierarchical Structure Reasoning

# 摘要

> 结构推理是大型语言模型 (LLMs) 的核心能力，使其能够处理结构化常识并解答多跳问题。然而，现有结构推理基准主要聚焦于水平和坐标结构（例如图），却忽视了其中的层级关系。层级结构推理对人类认知至关重要，尤其在记忆组织和问题解决方面。它在信息抽取和决策制定等现实任务中也起着关键作用。为填补这一空白，我们提出了 HiBench，这是首个从初始结构生成到最终熟练度评估的完整框架，旨在系统性地评估 LLMs 的层级推理能力。HiBench 包括六个代表性场景，涵盖基础与实际应用，并包含 30 个不同层级复杂度的任务，总共有 39,519 个查询。为了全面评估 LLMs，我们开发了五个能力维度，描述了对层级结构理解的不同方面。通过评估来自 10 个模型系列的 20 个 LLMs，我们揭示了它们的能力与局限：1）现有 LLMs 在基本层级推理任务中表现出色；2）它们仍难以处理更复杂的结构和隐式层级表示，尤其在结构修改和文本推理方面。基于这些发现，我们创建了一个小巧但设计精良的指令数据集，在所有任务中平均提升了 LLMs 在 HiBench 上的表现：Llama-3.1-8B 提升了 88.84%，Qwen2.5-7B 提升了 31.38%。HiBench 数据集和工具包在此处可用（https://github.com/jzzzzh/HiBench），以鼓励进一步的评估。


> Structure reasoning is a fundamental capability of large language models (LLMs), enabling them to reason about structured commonsense and answer multi-hop questions. However, existing benchmarks for structure reasoning mainly focus on horizontal and coordinate structures (\emph{e.g.} graphs), overlooking the hierarchical relationships within them. Hierarchical structure reasoning is crucial for human cognition, particularly in memory organization and problem-solving. It also plays a key role in various real-world tasks, such as information extraction and decision-making. To address this gap, we propose HiBench, the first framework spanning from initial structure generation to final proficiency assessment, designed to benchmark the hierarchical reasoning capabilities of LLMs systematically. HiBench encompasses six representative scenarios, covering both fundamental and practical aspects, and consists of 30 tasks with varying hierarchical complexity, totaling 39,519 queries. To evaluate LLMs comprehensively, we develop five capability dimensions that depict different facets of hierarchical structure understanding. Through extensive evaluation of 20 LLMs from 10 model families, we reveal key insights into their capabilities and limitations: 1) existing LLMs show proficiency in basic hierarchical reasoning tasks; 2) they still struggle with more complex structures and implicit hierarchical representations, especially in structural modification and textual reasoning. Based on these findings, we create a small yet well-designed instruction dataset, which enhances LLMs' performance on HiBench by an average of 88.84\% (Llama-3.1-8B) and 31.38\% (Qwen2.5-7B) across all tasks. The HiBench dataset and toolkit are available here, https://github.com/jzzzzh/HiBench, to encourage evaluation.

[Arxiv](https://arxiv.org/abs/2503.00912)