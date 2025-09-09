# LESER：电子商务中基于搜索引擎反馈强化的学习扩展

发布时间：2025年09月05日

`强化学习` `零售与电商`

> LESER: Learning to Expand via Search Engine-feedback Reinforcement in e-Commerce

# 摘要

> 电商搜索中的用户查询往往模糊、简短且信息不全，导致检索系统难以与结构化产品目录精准匹配。用户意图的“一对多”特性进一步加剧了这一挑战——单个查询可能暗含多样化甚至相互冲突的需求。现有方法（包括神经查询扩展和基于提示的LLM方法）在实际应用中表现欠佳：它们难以捕捉用户意图的细微差别，常生成违反平台约束的输出，且依赖的工作流在生产环境中难以扩展。我们提出了基于搜索引擎反馈强化的学习扩展框架（LESER），这是一种利用实时搜索引擎反馈作为监督来微调上下文感知LLM的创新框架。LESER将查询扩展转化为检索优化任务，并借助组相对策略优化直接从相关性和覆盖率指标中学习。LESER经过训练可对搜索结果进行推理，生成符合平台规则和检索目标的高质量查询扩展。我们在大规模真实电商数据集上对LESER进行了评估，结果显示其在离线和在线场景中均有显著提升。研究表明，LESER不仅提高了语义覆盖率和检索相关性，还显著提升了用户参与度，成为现代搜索系统的实用且可扩展解决方案。

> User queries in e-commerce search are often vague, short, and underspecified, making it difficult for retrieval systems to match them accurately against structured product catalogs. This challenge is amplified by the one-to-many nature of user intent, where a single query can imply diverse and competing needs. Existing methods, including neural query expansion and prompting-based LLM approaches, fall short in real-world settings: they struggle to capture nuanced user intent, often generate outputs that violate platform constraints, and rely on workflows that are difficult to scale in production. We propose Learning to Expand via Search Engine-feedback Reinforcement (LESER), a novel framework that fine-tunes a context-aware LLM using real-time search engine feedback as supervision. LESER formulates query expansion as a retrieval optimization task and leverages Group Relative Policy Optimization to learn directly from relevance and coverage metrics. LESER is trained to reason over search results and produce high quality query expansions that align with platform rules and retrieval objectives. We evaluate LESER on large-scale, real-world e-commerce datasets, demonstrating substantial improvements in both offline and online settings. Our results show that LESER not only enhances semantic coverage and retrieval relevance but also delivers measurable gains in user engagement, making it a practical and scalable solution for modern search systems.

[Arxiv](https://arxiv.org/abs/2509.05570)