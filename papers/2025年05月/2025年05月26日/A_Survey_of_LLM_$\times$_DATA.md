# # LLM与数据综述

发布时间：2025年05月26日

`LLM应用` `数据管理` `数据科学`

> A Survey of LLM $\times$ DATA

# 摘要

> 大型语言模型（LLM）与数据管理（DATA）的整合正在重塑这两个领域。本综述全面探讨了它们之间的双向关系。一方面，DATA4LLM涵盖了大规模数据处理、存储与服务，为LLM在预训练、后训练、检索增强生成及智能体工作流等阶段提供高质量、多样化且及时的数据支持：（i）LLM数据处理包括可扩展的数据获取、去重、过滤、选择、领域混合与合成增强；（ii）LLM数据存储聚焦于高效的数据与模型格式、分布式异构存储层级、KV缓存管理及容错检查点；（iii）LLM数据服务则应对RAG（如知识后处理）、LLM推理（如提示压缩、数据溯源）及训练策略（如数据打包与混洗）中的挑战。另一方面，在LLM4DATA中，LLMs正崛起为通用的数据管理引擎。我们综述了近期在（i）数据操作（自动数据清洗、集成、发现）、（ii）数据分析（涵盖结构化、半结构化与非结构化数据的推理）以及（iii）系统优化（如配置调优、查询改写、异常诊断）方面的进展，这些均得益于检索增强提示、任务专用微调及多智能体协作等LLM技术的推动。

> The integration of large language model (LLM) and data management (DATA) is rapidly redefining both domains. In this survey, we comprehensively review the bidirectional relationships. On the one hand, DATA4LLM, spanning large-scale data processing, storage, and serving, feeds LLMs with high quality, diversity, and timeliness of data required for stages like pre-training, post-training, retrieval-augmented generation, and agentic workflows: (i) Data processing for LLMs includes scalable acquisition, deduplication, filtering, selection, domain mixing, and synthetic augmentation; (ii) Data Storage for LLMs focuses on efficient data and model formats, distributed and heterogeneous storage hierarchies, KV-cache management, and fault-tolerant checkpointing; (iii) Data serving for LLMs tackles challenges in RAG (e.g., knowledge post-processing), LLM inference (e.g., prompt compression, data provenance), and training strategies (e.g., data packing and shuffling). On the other hand, in LLM4DATA, LLMs are emerging as general-purpose engines for data management. We review recent advances in (i) data manipulation, including automatic data cleaning, integration, discovery; (ii) data analysis, covering reasoning over structured, semi-structured, and unstructured data, and (iii) system optimization (e.g., configuration tuning, query rewriting, anomaly diagnosis), powered by LLM techniques like retrieval-augmented prompting, task-specialized fine-tuning, and multi-agent collaboration.

[Arxiv](https://arxiv.org/abs/2505.18458)