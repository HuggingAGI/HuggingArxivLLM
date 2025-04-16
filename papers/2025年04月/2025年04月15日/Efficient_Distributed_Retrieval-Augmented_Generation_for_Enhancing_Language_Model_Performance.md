# # 高效分布式检索增强生成：提升语言模型性能

发布时间：2025年04月15日

`RAG` `边缘计算` `分布式系统`

> Efficient Distributed Retrieval-Augmented Generation for Enhancing Language Model Performance

# 摘要

> 小型语言模型（SLMs）虽适合在资源有限的边缘设备上部署，但性能受限。检索增强生成（RAG）通过整合外部数据库，无需大量再训练，能有效提升模型表现。然而，公共数据库和用户文档通常分别位于云端和设备端，而现有RAG方案多为集中式。为此，我们提出DRAGON，一个分布式RAG框架，通过结合通用与个性化知识增强设备端SLMs，同时保护文档隐私。DRAGON将多文档RAG分解为云端和设备端独立运行的并行token生成过程，并采用新设计的Speculative Aggregation算法，减少两端的频繁同步。此外，还引入了基于实时网络条件的调度算法，选择最优聚合端。真实测试显示，DRAGON性能显著提升，与集中式RAG相比，独立SLM增益提升1.9倍，延迟大幅降低，且TTFT开销微乎其微。

> Small language models (SLMs) support efficient deployments on resource-constrained edge devices, but their limited capacity compromises inference performance. Retrieval-augmented generation (RAG) is a promising solution to enhance model performance by integrating external databases, without requiring intensive on-device model retraining. However, large-scale public databases and user-specific private contextual documents are typically located on the cloud and the device separately, while existing RAG implementations are primarily centralized. To bridge this gap, we propose DRAGON, a distributed RAG framework to enhance on-device SLMs through both general and personal knowledge without the risk of leaking document privacy. Specifically, DRAGON decomposes multi-document RAG into multiple parallel token generation processes performed independently and locally on the cloud and the device, and employs a newly designed Speculative Aggregation, a dual-side speculative algorithm to avoid frequent output synchronization between the cloud and device. A new scheduling algorithm is further introduced to identify the optimal aggregation side based on real-time network conditions. Evaluations on real-world hardware testbed demonstrate a significant performance improvement of DRAGON-up to 1.9x greater gains over standalone SLM compared to the centralized RAG, substantial reduction in per-token latency, and negligible Time to First Token (TTFT) overhead.

[Arxiv](https://arxiv.org/abs/2504.11197)