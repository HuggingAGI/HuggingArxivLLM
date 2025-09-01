# Anemoi：基于智能体间通信的半中心化多智能体系统——Coral Protocol的MCP服务器

发布时间：2025年08月27日

`Agent` `基础理论`

> Anemoi: A Semi-Centralized Multi-agent System Based on Agent-to-Agent Communication MCP server from Coral Protocol

# 摘要

> 通用多智能体系统（MAS）的最新进展大多采用上下文工程加集中式范式，即由规划器智能体通过单向提示传递来协调多个工作智能体。尽管在强规划器模型下表现有效，但这种设计存在两个关键缺陷：（1）对规划器能力的依赖性过强，当规划器由较小的LLM驱动时，性能会显著下降；（2）智能体间通信受限，协作依赖成本高昂的提示拼接和上下文注入，造成冗余和信息丢失。为解决这些问题，我们提出Anemoi——一种基于Coral协议的智能体到智能体（A2A）通信MCP服务器构建的半集中式MAS。与传统设计不同，Anemoi支持智能体间结构化的直接协作，让所有智能体能够实时监控进度、评估结果、识别瓶颈并提出改进方案。这种范式降低了对单一规划器的依赖，支持自适应计划更新，并减少了冗余上下文传递，从而实现更具可扩展性和成本效益的执行。在GAIA基准测试中，当使用小型LLM（GPT-4.1-mini）作为规划器时，Anemoi的准确率达到52.73%，在相同LLM设置下，比最强的开源基线OWL（43.63%）高出9.09%。我们的实现已在https://github.com/Coral-Protocol/Anemoi开源。

> Recent advances in generalist multi-agent systems (MAS) have largely followed a context-engineering plus centralized paradigm, where a planner agent coordinates multiple worker agents through unidirectional prompt passing. While effective under strong planner models, this design suffers from two critical limitations: (1) strong dependency on the planner's capability, which leads to degraded performance when a smaller LLM powers the planner; and (2) limited inter-agent communication, where collaboration relies on costly prompt concatenation and context injection, introducing redundancy and information loss. To address these challenges, we propose Anemoi, a semi-centralized MAS built on the Agent-to-Agent (A2A) communication MCP server from Coral Protocol. Unlike traditional designs, Anemoi enables structured and direct inter-agent collaboration, allowing all agents to monitor progress, assess results, identify bottlenecks, and propose refinements in real time. This paradigm reduces reliance on a single planner, supports adaptive plan updates, and minimizes redundant context passing, resulting in more scalable and cost-efficient execution. Evaluated on the GAIA benchmark, Anemoi achieved 52.73% accuracy with a small LLM (GPT-4.1-mini) as the planner, surpassing the strongest open-source baseline OWL (43.63%) by +9.09% under identical LLM settings. Our implementation is publicly available at https://github.com/Coral-Protocol/Anemoi.

[Arxiv](https://arxiv.org/abs/2508.17068)