# Cosmos：基于CXL的全内存系统，实现近似最近邻搜索

发布时间：2025年05月21日

`RAG` `大数据` `计算机体系结构`

> Cosmos: A CXL-Based Full In-Memory System for Approximate Nearest Neighbor Search

# 摘要

> 检索增强生成（RAG）对于通过注入从外部来源提取的适当上下文来提高大型语言模型的质量至关重要。RAG需要在十亿规模的向量数据库上进行高吞吐量、低延迟的近似最近邻搜索（ANNS）。传统的DRAM/SSD解决方案面临容量和延迟限制，而专用硬件或RDMA集群则缺乏灵活性或带来网络开销。我们提出了Cosmos，通过在CXL内存设备中集成通用处理核心，实现完整的ANNS卸载，并引入基于秩的并行距离计算以充分利用内存带宽。我们还提出了一种基于集群间邻近性的感知数据放置方法，以平衡CXL设备上的搜索负载。在SIFT1B和DEEP1B数据集上的评估表明，与基线CXL系统相比，Cosmos的吞吐量提高了6.72倍，与最先进的CXL基解决方案相比提高了2.35倍，证明了其在RAG流水线中的可扩展性。

> Retrieval-Augmented Generation (RAG) is crucial for improving the quality of large language models by injecting proper contexts extracted from external sources. RAG requires high-throughput, low-latency Approximate Nearest Neighbor Search (ANNS) over billion-scale vector databases. Conventional DRAM/SSD solutions face capacity/latency limits, whereas specialized hardware or RDMA clusters lack flexibility or incur network overhead. We present Cosmos, integrating general-purpose cores within CXL memory devices for full ANNS offload and introducing rank-level parallel distance computation to maximize memory bandwidth. We also propose an adjacency-aware data placement that balances search loads across CXL devices based on inter-cluster proximity. Evaluations on SIFT1B and DEEP1B traces show that Cosmos achieves up to 6.72x higher throughput than the baseline CXL system and 2.35x over a state-of-the-art CXL-based solution, demonstrating scalability for RAG pipelines.

[Arxiv](https://arxiv.org/abs/2505.16096)