# 借助知识图谱与大语言模型推理，助力仓储规划优化，精准识别运营瓶颈

发布时间：2025年07月23日

`LLM应用` `供应链管理`

> Leveraging Knowledge Graphs and LLM Reasoning to Identify Operational Bottlenecks for Warehouse Planning Assistance

# 摘要

> 仓库运营中的离散事件模拟（DES）会产生大量复杂的数据，分析这些数据以找出瓶颈和低效环节是一项既重要又具挑战性的任务，通常需要大量的人工投入或专业工具。我们的框架结合了知识图谱（KGs）和基于大型语言模型（LLM）的智能体，专门用于分析仓库运营中的DES数据。首先，我们将原始的DES数据转化为一个语义丰富的知识图谱，其中详细记录了模拟事件与实体之间的关系。接着，一个基于LLM的智能体通过迭代推理的方式，自动生成一系列相互关联的子问题。针对每个子问题，智能体会自动生成Cypher查询语句与知识图谱进行交互，从中提取所需信息，并通过自我反思机制不断优化和纠正可能出现的错误。这种适应性、迭代性和自我纠错的过程，使得智能体能够像人类一样精准地识别出运营中的问题。我们通过设备故障和流程异常的测试案例，验证了这一方法在仓库瓶颈识别方面的优越性。在处理运营相关问题时，它几乎完美地识别出了所有低效环节。而对于复杂的调查问题，它也展现出了卓越的诊断能力，能够发现那些微妙且相互关联的问题。这项研究将仿真建模与人工智能（KG+LLM）相结合，提供了一种更直观的方法，帮助我们快速获得有价值的见解，缩短了从数据到洞察的时间，并实现了仓库低效环节的自动化评估和诊断。

> Analyzing large, complex output datasets from Discrete Event Simulations (DES) of warehouse operations to identify bottlenecks and inefficiencies is a critical yet challenging task, often demanding significant manual effort or specialized analytical tools. Our framework integrates Knowledge Graphs (KGs) and Large Language Model (LLM)-based agents to analyze complex Discrete Event Simulation (DES) output data from warehouse operations. It transforms raw DES data into a semantically rich KG, capturing relationships between simulation events and entities. An LLM-based agent uses iterative reasoning, generating interdependent sub-questions. For each sub-question, it creates Cypher queries for KG interaction, extracts information, and self-reflects to correct errors. This adaptive, iterative, and self-correcting process identifies operational issues mimicking human analysis. Our DES approach for warehouse bottleneck identification, tested with equipment breakdowns and process irregularities, outperforms baseline methods. For operational questions, it achieves near-perfect pass rates in pinpointing inefficiencies. For complex investigative questions, we demonstrate its superior diagnostic ability to uncover subtle, interconnected issues. This work bridges simulation modeling and AI (KG+LLM), offering a more intuitive method for actionable insights, reducing time-to-insight, and enabling automated warehouse inefficiency evaluation and diagnosis.

[Arxiv](https://arxiv.org/abs/2507.17273)