# FlowTracer: 揭示AI训练集群网络路径使用不平衡的神器

发布时间：2024年10月22日

`LLM应用

**解释**：这篇论文主要讨论了分布式大型语言模型（LLM）训练对网络基础设施的挑战，并提出了FlowTracer工具来优化网络路由，提升分布式AI工作负载的性能。虽然论文涉及了网络基础设施的优化，但其核心关注点仍然是LLM在分布式环境中的应用和性能优化，因此将其分类为LLM应用。` `网络基础设施` `分布式计算`

> FlowTracer: A Tool for Uncovering Network Path Usage Imbalance in AI Training Clusters

# 摘要

> 随着AI工作负载的复杂性不断增加，尤其是分布式大型语言模型（LLM）训练，对并行数据中心和超级计算系统的网络基础设施带来了巨大挑战。尽管等成本多路径（ECMP）路由能够在并行路径上分配流量，但哈希冲突常常导致网络资源利用不均和性能瓶颈。本文提出的FlowTracer工具，旨在分析网络路径利用率并评估不同路由策略。FlowTracer通过提供详细的流量分布信息，帮助诊断网络效率问题，并识别性能下降的根源，如哈希冲突。通过流级别的洞察，FlowTracer帮助系统操作员优化路由，减少拥塞，提升分布式AI工作负载的性能。我们使用一个支持RoCEv2的叶脊网络集群，包含16个400-Gbps节点，展示了FlowTracer如何比较ECMP路由与静态配置网络的流量不平衡。实验结果表明，使用我们提出的新指标，不平衡减少了30%。

> The increasing complexity of AI workloads, especially distributed Large Language Model (LLM) training, places significant strain on the networking infrastructure of parallel data centers and supercomputing systems. While Equal-Cost Multi- Path (ECMP) routing distributes traffic over parallel paths, hash collisions often lead to imbalanced network resource utilization and performance bottlenecks. This paper presents FlowTracer, a tool designed to analyze network path utilization and evaluate different routing strategies. FlowTracer aids in debugging network inefficiencies by providing detailed visibility into traffic distribution and helping to identify the root causes of performance degradation, such as issues caused by hash collisions. By offering flow-level insights, FlowTracer enables system operators to optimize routing, reduce congestion, and improve the performance of distributed AI workloads. We use a RoCEv2-enabled cluster with a leaf-spine network and 16 400-Gbps nodes to demonstrate how FlowTracer can be used to compare the flow imbalances of ECMP routing against a statically configured network. The example showcases a 30% reduction in imbalance, as measured by a new metric we introduce.

[Arxiv](https://arxiv.org/abs/2410.17078)