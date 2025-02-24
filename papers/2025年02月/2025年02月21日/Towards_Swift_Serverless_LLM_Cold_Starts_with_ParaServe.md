# # ParaServe：实现LLM快速无服务器冷启动的方法

发布时间：2025年02月21日

`LLM应用

摘要中讨论了大语言模型（LLMs）在无服务器计算环境中的应用，特别是优化LLM推理服务的冷启动延迟和性能。这属于LLM在实际应用中的优化和系统设计，因此归类为LLM应用。` `云计算` `云服务`

> Towards Swift Serverless LLM Cold Starts with ParaServe

# 摘要

> 随着大语言模型（LLMs）的激增，无服务器计算成为LLM推理服务的新选择。然而，由于模型规模庞大，无服务器LLM服务在从远程存储获取模型时面临显著的冷启动延迟和服务级别目标（SLO）违约问题。我们提出ParaServe，一个通过创新性地采用管道并行来最小化冷启动延迟的无服务器LLM服务系统。ParaServe采用两级分层设计：在集群级别，根据用户SLO确定最佳并行度，并将GPU工作者分布在服务器之间以减少网络干扰；在工作者级别，重叠模型获取、加载和运行时初始化以进一步加速冷启动。此外，ParaServe引入了管道合并，将并行组合并回单个工作者，以维持对暖请求的最优性能。全面的实验评估表明，与基线相比，ParaServe将冷启动延迟减少了4.7倍，并将SLO达成率提高了1.74倍。

> With the surge in number of large language models (LLMs), the industry turns to serverless computing for LLM inference serving. However, serverless LLM serving suffers from significant cold start latency and service level objective (SLO) violations due to the substantial model size, which leads to prolonged model fetching time from remote storage. We present ParaServe, a serverless LLM serving system that minimizes cold start latency through the novel use of pipeline parallelism. Our insight is that by distributing model parameters across multiple GPU servers, we can utilize their aggregated network bandwidth to concurrently fetch different parts of the model. ParaServe adopts a two-level hierarchical design. At the cluster level, ParaServe determines the optimal degree of parallelism based on user SLOs and carefully places GPU workers across servers to reduce network interference. At the worker level, ParaServe overlaps model fetching, loading, and runtime initialization to further accelerate cold starts. Additionally, ParaServe introduces pipeline consolidation, which merges parallel groups back to individual workers to maintain optimal performance for warm requests. Our comprehensive evaluations under diverse settings demonstrate that ParaServe reduces the cold start latency by up to 4.7x and improves SLO attainment by up to 1.74x compared to baselines.

[Arxiv](https://arxiv.org/abs/2502.15524)