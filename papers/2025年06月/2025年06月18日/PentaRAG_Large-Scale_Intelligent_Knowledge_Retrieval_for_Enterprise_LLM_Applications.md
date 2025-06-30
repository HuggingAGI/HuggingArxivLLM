# PentaRAG：为企业级大语言模型应用提供大规模智能知识检索

发布时间：2025年06月18日

`RAG` `问答系统`

> PentaRAG: Large-Scale Intelligent Knowledge Retrieval for Enterprise LLM Applications

# 摘要

> 企业级部署大型语言模型（LLM）需要处理动态变化的文档集合，要求亚秒级延迟和可预测的GPU成本，而传统检索增强生成（RAG）流水线仅能满足部分需求。我们提出了一种五层模块PentaRAG，它通过两个即时缓存（固定键值和语义）、利用LLM自身权重的内存召回模式、自适应会话内存以及传统的检索增强层来路由每个查询。基于Mistral-8B、Milvus和vLLM实现的PentaRAG系统，能够从低延迟缓存中快速回答大部分重复或语义相似的问题，同时对新查询保持完整的检索能力。

在TriviaQA领域，结合LoRA微调与内存召回层，答案相似度较基础模型提升了约8%，事实正确性提升了约16%。在九个会话的运行模拟中，缓存预热将平均延迟从数秒降至低于一秒，并将流量引导至快速路径。资源效率测试表明，PentaRAG将平均GPU时间降至每查询0.248秒，约为朴素RAG基线的一半，并在我们的配置下实现每秒约100,000查询的吞吐量。这些结果证明，分层路由策略可以在生产级RAG系统中同时实现新鲜度、速度和效率。

> Enterprise deployments of large-language model (LLM) demand continuously changing document collections with sub-second latency and predictable GPU cost requirements that classical Retrieval-Augmented Generation (RAG) pipelines only partially satisfy. We present PentaRAG, a five-layer module that routes each query through two instant caches (fixed key-value and semantic), a memory-recall mode that exploits the LLM's own weights, an adaptive session memory, and a conventional retrieval-augmentation layer. Implemented with Mistral-8B, Milvus and vLLM, the system can answer most repeated or semantically similar questions from low-latency caches while retaining full retrieval for novel queries. On the TriviaQA domain, LoRA fine-tuning combined with the memory-recall layer raises answer similarity by approximately 8% and factual correctness by approximately 16% over the base model. Under a nine-session runtime simulation, cache warming reduces mean latency from several seconds to well below one second and shifts traffic toward the fast paths. Resource-efficiency tests show that PentaRAG cuts average GPU time to 0.248 seconds per query, roughly half that of a naive RAG baseline, and sustains an aggregate throughput of approximately 100,000 queries per second on our setup. These results demonstrate that a layered routing strategy can deliver freshness, speed, and efficiency simultaneously in production-grade RAG systems.

[Arxiv](https://arxiv.org/abs/2506.21593)