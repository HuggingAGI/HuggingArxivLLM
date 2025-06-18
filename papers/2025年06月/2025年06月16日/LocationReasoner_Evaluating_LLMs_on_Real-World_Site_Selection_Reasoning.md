# LocationReasoner：基于真实场景选址决策推理的LLMs评测

发布时间：2025年06月16日

`LLM应用`

> LocationReasoner: Evaluating LLMs on Real-World Site Selection Reasoning

# 摘要

> 大型语言模型（LLMs）特别是经过强化后训练的模型（如OpenAI o1和DeepSeek-R1）展现出令人瞩目的推理能力。然而，这些能力主要在数学问题解决和代码生成等特定领域得到了验证，关于这些推理技能能否推广到复杂的真实世界场景仍存在疑问。为此，我们开发了LocationReasoner——一个评估LLMs在现实世界选址任务中推理能力的基准测试。在这一任务中，模型需通过推理复杂的空间、环境和物流约束来识别可行的选址。该基准测试包含300多个难度各异的精心设计的查询，并提供了一个支持基于约束的选址搜索的沙盒环境，其中集成了内部开发的工具。评估结果显示，在现实场景中，最先进的推理模型相较于不具备推理能力的早期模型仅有有限的改进，即使是最新的OpenAI o4模型在30%的选址任务上也未能成功。此外，像ReAct和Reflexion这样的智能体策略常常陷入过度推理，导致比直接代码生成提示更糟糕的结果。我们揭示了LLMs在整体性和非线性推理方面的关键局限性，并发布了LocationReasoner，以推动具备在现实世界决策任务中进行稳健、基于事实推理的LLMs和智能体的发展。我们的基准测试代码和数据可在https://github.com/miho-koda/LocationReasoner获取。

> Recent advances in large language models (LLMs), particularly those enhanced through reinforced post-training, have demonstrated impressive reasoning capabilities, as exemplified by models such as OpenAI o1 and DeepSeek-R1. However, these capabilities are predominantly benchmarked on domains like mathematical problem solving and code generation -- leaving open the question of whether such reasoning skills generalize to complex, real-world scenarios. In this paper, we introduce LocationReasoner, a benchmark designed to evaluate LLMs' reasoning abilities in the context of real-world site selection, where models must identify feasible locations by reasoning over diverse and complicated spatial, environmental, and logistical constraints. The benchmark comprises over 300 carefully crafted queries of varying difficulty levels, supported by a sandbox environment with in-house tools for constraint-based location search. Extensive evaluations reveal that state-of-the-art reasoning models offer limited improvement over their non-reasoning predecessors in real-world contexts, with even the latest OpenAI o4 model failing on 30% of site selection tasks. Moreover, agentic strategies such as ReAct and Reflexion often suffer from over-reasoning, leading to worse outcomes than direct code-generation prompting. With key limitations of LLMs in holistic and non-linear reasoning highlighted, we release LocationReasoner to foster the development of LLMs and agents capable of robust, grounded reasoning in real-world decision-making tasks. Codes and data for our benchmark are available at https://github.com/miho-koda/LocationReasoner.

[Arxiv](https://arxiv.org/abs/2506.13841)