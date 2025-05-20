# # LightRetriever: 基于LLM的混合检索架构，实现千倍加速的查询推理

发布时间：2025年05月18日

`LLM应用` `信息检索` `搜索引擎`

> LightRetriever: A LLM-based Hybrid Retrieval Architecture with 1000x Faster Query Inference

# 摘要

> 基于大型语言模型（LLMs）的混合检索技术通过将查询和文档编码为低维密集或高维稀疏向量，利用向量相似性进行相关文档检索。文档预先离线编码，而查询实时到达，因此需要高效的在线查询编码器。尽管LLMs显著提升了检索能力，但运行参数量大的LLMs会降低查询推理速度并增加资源需求。本文提出了一种名为LightRetriever的轻量化LLM混合检索器。我们的方法保留完整的LLM用于文档编码，但将查询编码的工作量减少到嵌入查找级别。与在H800 GPU上运行完整的LLM相比，我们的方法在GPU加速下实现了超过1000倍的查询推理加速，无GPU情况下也实现了20倍的加速。在大规模检索基准上的实验表明，我们的方法在各种检索任务中表现优异，平均保留了95%的完整模型性能。

> Large Language Models (LLMs)-based hybrid retrieval uses LLMs to encode queries and documents into low-dimensional dense or high-dimensional sparse vectors. It retrieves documents relevant to search queries based on vector similarities. Documents are pre-encoded offline, while queries arrive in real-time, necessitating an efficient online query encoder. Although LLMs significantly enhance retrieval capabilities, serving deeply parameterized LLMs slows down query inference throughput and increases demands for online deployment resources. In this paper, we propose LightRetriever, a novel LLM-based hybrid retriever with extremely lightweight query encoders. Our method retains a full-sized LLM for document encoding, but reduces the workload of query encoding to no more than an embedding lookup. Compared to serving a full-sized LLM on an H800 GPU, our approach achieves over a 1000x speedup for query inference with GPU acceleration, and even a 20x speedup without GPU. Experiments on large-scale retrieval benchmarks demonstrate that our method generalizes well across diverse retrieval tasks, retaining an average of 95% full-sized performance.

[Arxiv](https://arxiv.org/abs/2505.12260)