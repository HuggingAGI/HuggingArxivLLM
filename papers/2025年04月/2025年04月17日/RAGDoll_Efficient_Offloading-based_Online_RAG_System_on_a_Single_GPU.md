# RAGDoll：基于高效卸载的单GPU在线RAG系统

发布时间：2025年04月17日

`RAG` `消费电子` `软件服务`

> RAGDoll: Efficient Offloading-based Online RAG System on a Single GPU

# 摘要

> 检索增强生成（RAG）通过整合相关外部知识来提升大型语言模型（LLM）的生成质量。然而，在资源受限的消费级平台上部署RAG面临着挑战，因为模型和知识库的规模日益增大，而设备的内存却十分有限。在本研究中，我们提出了RAGDoll——一个资源高效型、自我适应的RAG服务系统，该系统与LLMs深度集成，专门针对资源受限的平台进行优化。RAGDoll基于一个关键洞察：RAG检索与LLM生成对计算和内存的需求存在显著差异，而传统串行工作流程下会导致大量空闲时间并造成资源利用率低下。基于这一洞察，RAGDoll将检索与生成解耦为并行管道，并结合联合内存分配和动态批处理调度策略，从而在不同硬件设备和负载条件下实现资源利用率的最优化。通过大量实验验证，RAGDoll能够有效适应多种硬件配置和LLM规模，与基于vLLM的串行RAG系统相比，平均延迟实现了高达3.6倍的性能提升。

> Retrieval-Augmented Generation (RAG) enhances large language model (LLM) generation quality by incorporating relevant external knowledge. However, deploying RAG on consumer-grade platforms is challenging due to limited memory and the increasing scale of both models and knowledge bases. In this work, we introduce RAGDoll, a resource-efficient, self-adaptive RAG serving system integrated with LLMs, specifically designed for resource-constrained platforms. RAGDoll exploits the insight that RAG retrieval and LLM generation impose different computational and memory demands, which in a traditional serial workflow result in substantial idle times and poor resource utilization. Based on this insight, RAGDoll decouples retrieval and generation into parallel pipelines, incorporating joint memory placement and dynamic batch scheduling strategies to optimize resource usage across diverse hardware devices and workloads. Extensive experiments demonstrate that RAGDoll adapts effectively to various hardware configurations and LLM scales, achieving up to 3.6 times speedup in average latency compared to serial RAG systems based on vLLM.

[Arxiv](https://arxiv.org/abs/2504.15302)