# 移动边缘LLM服务的自适应上下文缓存

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要讨论了在移动边缘环境中部署大型语言模型（LLM）时面临的挑战，并提出了一种自适应上下文缓存（ACC）框架来优化缓存策略，从而提高LLM服务的效率。虽然提到了RAG（Retrieval-Augmented Generation）作为背景，但论文的核心内容是针对LLM在边缘计算环境中的应用优化，因此应归类为“LLM应用”。` `边缘计算` `缓存管理`

> Adaptive Contextual Caching for Mobile Edge Large Language Model Service

# 摘要

> 移动边缘LLM部署面临计算资源和网络带宽有限的挑战。尽管RAG通过整合外部知识库缓解了部分问题，但低效的缓存管理仍可能导致高延迟和频繁更新。为此，我们提出了自适应上下文缓存（ACC）框架，通过主动缓存语义相关数据来预测用户需求。ACC利用深度强化学习（DRL）优化缓存策略，平衡用户上下文、文档相似性和缓存未命中开销。实验显示，ACC在11次训练后缓存命中率超过80%，优于FIFO、LRU和仅语义缓存，并将检索延迟降低40%。此外，ACC还将本地缓存开销降低55%，在资源受限的边缘环境中实现了高效的低延迟LLM服务。

> Mobile edge Large Language Model (LLM) deployments face inherent constraints, such as limited computational resources and network bandwidth. Although Retrieval-Augmented Generation (RAG) mitigates some challenges by integrating external knowledge bases, inefficient cache management can still result in high retrieval latency and frequent cache updates. To address these issues, we propose an Adaptive Contextual Caching (ACC) framework that anticipates user needs by proactively caching semantically relevant data for mobile-edge LLMs. ACC utilizes a deep reinforcement learning (DRL) module to refine cache replacement policies, balancing user context, document similarity, and the overhead associated with cache misses. Experimental results demonstrate that ACC increases cache hit rates to over 80\% after only 11 training episodes, outperforming FIFO, LRU, and semantic-only caching while reducing retrieval latency by up to 40\%. In particular, ACC also reduces local caching overhead (i.e., the cost of updating the cache when a miss occurs) by as much as 55\%, enabling scalable, low-latency LLM services in resource-constrained edge environments.

[Arxiv](https://arxiv.org/abs/2501.09383)