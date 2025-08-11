# RCR-Router：具备结构化记忆的多智能体LLM系统高效角色感知上下文路由方案。

发布时间：2025年08月06日

`LLM应用` `多智能体系统` `问答系统`

> RCR-Router: Efficient Role-Aware Context Routing for Multi-Agent LLM Systems with Structured Memory

# 摘要

> 多智能体大型语言模型 (LLM) 在复杂推理和协作决策任务中表现突出。然而，现有的协调方案大多依赖静态或全上下文路由策略，导致令牌消耗过多、内存冗余暴露以及交互轮次间适应性受限。我们推出了 RCR-Router，一个模块化且具备角色感知的上下文路由框架，旨在优化多智能体 LLM 的高效协作。据我们所知，这是首个基于严格令牌预算，动态为每个智能体选择与其角色和任务阶段相关的语义记忆子集的路由方法。通过轻量级评分策略引导内存选择，并将智能体输出逐步整合到共享内存存储中，以实现渐进式上下文细化。为更全面评估模型行为，我们提出了一种答案质量评分指标，不仅关注标准问答准确性，还捕捉 LLM 生成的解释。在 HotPotQA、MuSiQue 和 2WikiMultihop 三个多跳问答基准上的实验显示，RCR-Router 在减少令牌使用量（高达 30%）的同时，显著提升了或保持了答案质量。这些结果凸显了结构化内存路由和输出感知评估在推进可扩展多智能体 LLM 系统中的关键作用。

> Multi-agent large language model (LLM) systems have shown strong potential in complex reasoning and collaborative decision-making tasks. However, most existing coordination schemes rely on static or full-context routing strategies, which lead to excessive token consumption, redundant memory exposure, and limited adaptability across interaction rounds. We introduce RCR-Router, a modular and role-aware context routing framework designed to enable efficient, adaptive collaboration in multi-agent LLMs. To our knowledge, this is the first routing approach that dynamically selects semantically relevant memory subsets for each agent based on its role and task stage, while adhering to a strict token budget. A lightweight scoring policy guides memory selection, and agent outputs are iteratively integrated into a shared memory store to facilitate progressive context refinement. To better evaluate model behavior, we further propose an Answer Quality Score metric that captures LLM-generated explanations beyond standard QA accuracy. Experiments on three multi-hop QA benchmarks -- HotPotQA, MuSiQue, and 2WikiMultihop -- demonstrate that RCR-Router reduces token usage (up to 30%) while improving or maintaining answer quality. These results highlight the importance of structured memory routing and output-aware evaluation in advancing scalable multi-agent LLM systems.

[Arxiv](https://arxiv.org/abs/2508.04903)