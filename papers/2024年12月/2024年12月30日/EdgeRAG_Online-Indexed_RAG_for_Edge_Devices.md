# EdgeRAG：适用于边缘设备的在线索引型 RAG

发布时间：2024年12月30日

`RAG` `边缘计算` `检索增强生成`

> EdgeRAG: Online-Indexed RAG for Edge Devices

# 摘要

> 在资源受限的边缘设备上部署检索增强生成（RAG）颇具挑战，原因是内存和处理能力有限。在本研究中，我们提出了 EdgeRAG，其通过修剪簇内嵌入并在检索时按需生成嵌入来应对内存限制。为规避大尾簇生成嵌入的延迟，EdgeRAG 预先计算并存储这些簇的嵌入，同时自适应缓存其余嵌入，以最大程度减少冗余计算并进一步优化延迟。BEIR 套件的结果显示，EdgeRAG 相比基线 IVF 索引大幅降低了延迟，且生成质量相近，同时能让我们评估的所有数据集都适配内存。

> Deploying Retrieval Augmented Generation (RAG) on resource-constrained edge devices is challenging due to limited memory and processing power. In this work, we propose EdgeRAG which addresses the memory constraint by pruning embeddings within clusters and generating embeddings on-demand during retrieval. To avoid the latency of generating embeddings for large tail clusters, EdgeRAG pre-computes and stores embeddings for these clusters, while adaptively caching remaining embeddings to minimize redundant computations and further optimize latency. The result from BEIR suite shows that EdgeRAG offers significant latency reduction over the baseline IVF index, but with similar generation quality while allowing all of our evaluated datasets to fit into the memory.

[Arxiv](https://arxiv.org/abs/2412.21023)