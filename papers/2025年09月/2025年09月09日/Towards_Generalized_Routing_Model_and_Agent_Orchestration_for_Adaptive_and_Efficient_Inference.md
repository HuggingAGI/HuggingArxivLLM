# 迈向通用路由：模型与智能体编排助力自适应高效推理

发布时间：2025年09月09日

`Agent` `基础理论`

> Towards Generalized Routing: Model and Agent Orchestration for Adaptive and Efficient Inference

# 摘要

> 大型语言模型（LLMs）与特定领域AI智能体的飞速发展，极大地拓展了AI驱动服务的生态系统。然而，用户查询高度多样化，往往跨越多个领域和任务类型，形成了复杂而异构的应用场景。这种多样性带来了一个核心路由难题：如何在兼顾性能与效率的同时，将每个查询精准导向合适的执行单元。为此，我们提出MoMA（模型与智能体混合框架）——一个集成了LLM与智能体路由的通用路由框架。MoMA基于对模型与智能体能力的深度理解，通过精准的意图识别与自适应路由策略，高效处理多样化查询，实现了效率与成本的最优平衡。具体而言，我们构建了详细的训练数据集，用于刻画不同路由模型结构下各类LLM的能力特征，从而确定每个LLM最适配的任务；在推理阶段，则将查询动态路由至性价比最优的LLM。

> The rapid advancement of large language models (LLMs) and domain-specific AI agents has greatly expanded the ecosystem of AI-powered services. User queries, however, are highly diverse and often span multiple domains and task types, resulting in a complex and heterogeneous landscape. This diversity presents a fundamental routing challenge: how to accurately direct each query to an appropriate execution unit while optimizing both performance and efficiency. To address this, we propose MoMA (Mixture of Models and Agents), a generalized routing framework that integrates both LLM and agent-based routing. Built upon a deep understanding of model and agent capabilities, MoMA effectively handles diverse queries through precise intent recognition and adaptive routing strategies, achieving an optimal balance between efficiency and cost. Specifically, we construct a detailed training dataset to profile the capabilities of various LLMs under different routing model structures, identifying the most suitable tasks for each LLM. During inference, queries are dynamically routed to the LLM with the best cost-performance efficiency. We also introduce an efficient agent selection strategy based on a context-aware state machine and dynamic masking. Experimental results demonstrate that the MoMA router offers superior cost-efficiency and scalability compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2509.07571)