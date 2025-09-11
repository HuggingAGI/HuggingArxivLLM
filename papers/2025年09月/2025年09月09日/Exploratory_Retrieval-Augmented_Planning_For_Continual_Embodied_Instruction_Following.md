# 面向持续具身指令跟随的探索式检索增强规划

发布时间：2025年09月09日

`Agent` `工业与制造`

> Exploratory Retrieval-Augmented Planning For Continual Embodied Instruction Following

# 摘要

> 本研究提出探索性检索增强规划（ExRAP）框架，专门用于解决具身智能体在动态非平稳环境中的持续指令跟随任务。该框架通过高效探索物理环境并构建环境上下文记忆，增强了大型语言模型（LLMs）的具身推理能力，进而将任务规划过程有效锚定在时变环境上下文中。在ExRAP中，面对多个持续指令跟随任务时，每个指令会被拆解为对环境上下文记忆的查询以及基于查询结果的任务执行。为高效处理这些需连续同步执行的多任务，我们将{基于信息的探索}融入基于LLM的规划过程，提出了探索集成式任务规划方案。结合记忆增强的查询评估机制，该集成方案不仅能更好地平衡环境上下文记忆的有效性与环境探索的负载，还能提升整体任务性能。此外，我们还为查询评估设计了{时间一致性优化}方案，以应对记忆中知识的固有衰减问题。通过在VirtualHome、ALFRED和CARLA平台上的实验验证，我们的方法在涉及不同指令规模、类型及非平稳程度的各类具身指令跟随场景中展现出稳健性，并且在目标成功率和执行效率上持续优于其他最先进的基于LLM的任务规划方法。

> This study presents an Exploratory Retrieval-Augmented Planning (ExRAP) framework, designed to tackle continual instruction following tasks of embodied agents in dynamic, non-stationary environments. The framework enhances Large Language Models' (LLMs) embodied reasoning capabilities by efficiently exploring the physical environment and establishing the environmental context memory, thereby effectively grounding the task planning process in time-varying environment contexts. In ExRAP, given multiple continual instruction following tasks, each instruction is decomposed into queries on the environmental context memory and task executions conditioned on the query results. To efficiently handle these multiple tasks that are performed continuously and simultaneously, we implement an exploration-integrated task planning scheme by incorporating the {information-based exploration} into the LLM-based planning process. Combined with memory-augmented query evaluation, this integrated scheme not only allows for a better balance between the validity of the environmental context memory and the load of environment exploration, but also improves overall task performance. Furthermore, we devise a {temporal consistency refinement} scheme for query evaluation to address the inherent decay of knowledge in the memory. Through experiments with VirtualHome, ALFRED, and CARLA, our approach demonstrates robustness against a variety of embodied instruction following scenarios involving different instruction scales and types, and non-stationarity degrees, and it consistently outperforms other state-of-the-art LLM-based task planning approaches in terms of both goal success rate and execution efficiency.

[Arxiv](https://arxiv.org/abs/2509.08222)