# FedSA-GCL: 一种结合个性化聚合与集群感知广播的半异步联邦图学习框架

发布时间：2025年07月24日

`其他` `社交网络` `图学习`

> FedSA-GCL: A Semi-Asynchronous Federated Graph Learning Framework with Personalized Aggregation and Cluster-Aware Broadcasting

# 摘要

> 联邦图学习（FGL）是一种分布式学习范式，能够在多个本地系统上的大规模子图上实现协作训练。然而，现有的 FGL 方法大多依赖同步通信，这导致了低效，并且在实际部署中常常不切实际。同时，目前的异步联邦学习（AFL）方法主要针对图像分类和自然语言处理等传统任务设计，没有考虑到图数据独特的拓扑特性。直接将这些方法应用于图学习可能会导致全局模型出现语义漂移和表示不一致的问题。为了解决这些挑战，我们提出了 FedSA-GCL，这是一种半异步联邦框架，通过一种新型的 ClusterCast 机制，结合客户端间标签分布差异和图拓扑特性，实现高效的训练。我们使用 Louvain 和 Metis 分裂算法在多个真实图数据集上评估 FedSA-GCL，并将其与 9 种基线方法进行对比。大量实验表明，我们的方法在强鲁棒性和优异效率方面表现出色，与基线相比，使用 Louvain 时平均高出 2.92%，使用 Metis 时平均高出 3.4%。

> Federated Graph Learning (FGL) is a distributed learning paradigm that enables collaborative training over large-scale subgraphs located on multiple local systems. However, most existing FGL approaches rely on synchronous communication, which leads to inefficiencies and is often impractical in real-world deployments. Meanwhile, current asynchronous federated learning (AFL) methods are primarily designed for conventional tasks such as image classification and natural language processing, without accounting for the unique topological properties of graph data. Directly applying these methods to graph learning can possibly result in semantic drift and representational inconsistency in the global model. To address these challenges, we propose FedSA-GCL, a semi-asynchronous federated framework that leverages both inter-client label distribution divergence and graph topological characteristics through a novel ClusterCast mechanism for efficient training. We evaluate FedSA-GCL on multiple real-world graph datasets using the Louvain and Metis split algorithms, and compare it against 9 baselines. Extensive experiments demonstrate that our method achieves strong robustness and outstanding efficiency, outperforming the baselines by an average of 2.92% with the Louvain and by 3.4% with the Metis.

[Arxiv](https://arxiv.org/abs/2507.18219)