# Zep: 智能体记忆的时间知识图谱架构

发布时间：2025年01月20日

`Agent

理由：这篇论文介绍了Zep，一种新型的AI代理内存层服务，专注于解决企业应用中的动态知识整合问题。Zep通过其核心组件Graphiti，能够动态整合非结构化对话数据和结构化业务数据，并在多个基准测试中表现出色。这些特点表明Zep是一个面向实际应用的AI代理系统，因此应归类为Agent。` `企业服务` `人工智能`

> Zep: A Temporal Knowledge Graph Architecture for Agent Memory

# 摘要

> 我们推出了Zep，一种新型的AI代理内存层服务，在深度记忆检索（DMR）基准测试中超越了当前最先进的MemGPT系统。Zep不仅在DMR中表现优异，还在更全面、更具挑战性的评估中脱颖而出，这些评估更贴近企业实际需求。现有的基于LLM的RAG框架通常局限于静态文档检索，而企业应用则需要从多种来源（如实时对话和业务数据）动态整合知识。Zep通过其核心组件Graphiti——一个时间感知的知识图谱引擎，解决了这一难题。Graphiti能够动态整合非结构化对话数据和结构化业务数据，同时保留历史关系。在DMR基准测试中，Zep以94.8%的准确率超越了MemGPT的93.4%。此外，Zep在更具挑战性的LongMemEval基准测试中也表现出色，该测试通过复杂的时间推理任务更好地模拟了企业场景。在此测试中，Zep的准确率提升了18.5%，同时响应延迟减少了90%。这些成果在跨会话信息合成和长期上下文维护等企业关键任务中尤为突出，充分证明了Zep在实际应用中的强大能力。

> We introduce Zep, a novel memory layer service for AI agents that outperforms the current state-of-the-art system, MemGPT, in the Deep Memory Retrieval (DMR) benchmark. Additionally, Zep excels in more comprehensive and challenging evaluations than DMR that better reflect real-world enterprise use cases. While existing retrieval-augmented generation (RAG) frameworks for large language model (LLM)-based agents are limited to static document retrieval, enterprise applications demand dynamic knowledge integration from diverse sources including ongoing conversations and business data. Zep addresses this fundamental limitation through its core component Graphiti -- a temporally-aware knowledge graph engine that dynamically synthesizes both unstructured conversational data and structured business data while maintaining historical relationships. In the DMR benchmark, which the MemGPT team established as their primary evaluation metric, Zep demonstrates superior performance (94.8% vs 93.4%). Beyond DMR, Zep's capabilities are further validated through the more challenging LongMemEval benchmark, which better reflects enterprise use cases through complex temporal reasoning tasks. In this evaluation, Zep achieves substantial results with accuracy improvements of up to 18.5% while simultaneously reducing response latency by 90% compared to baseline implementations. These results are particularly pronounced in enterprise-critical tasks such as cross-session information synthesis and long-term context maintenance, demonstrating Zep's effectiveness for deployment in real-world applications.

[Arxiv](https://arxiv.org/abs/2501.13956)