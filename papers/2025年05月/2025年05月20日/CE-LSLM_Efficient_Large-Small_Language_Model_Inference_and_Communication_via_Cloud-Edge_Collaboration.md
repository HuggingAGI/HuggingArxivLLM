# CE-LSLM：云边协作实现高效大-小语言模型推理与通信

发布时间：2025年05月20日

`LLM应用` `人工智能`

> CE-LSLM: Efficient Large-Small Language Model Inference and Communication via Cloud-Edge Collaboration

# 摘要

> 6G通信中的新兴智能服务场景对低时延、高可靠性和隐私保护提出了严苛要求。生成式大语言模型（LLMs）正逐渐成为语义通信与计算融合的关键推动力。然而，由于边缘设备计算资源有限且异构终端接入复杂度增加，现有集中式推理方法难以满足边缘侧推理任务在响应效率和数据隐私方面的双重需求。

为解决这些挑战，本文提出一种全新的协作推理架构，将基于云端的LLMs与边缘部署的小语言模型（SLMs）相结合，实现语义级中间状态的动态调度与共享，并为6G网络量身打造一体化计算-通信范式。具体而言，我们引入键值（KV）缓存复用机制，通过云端上下文引导增强边缘模型语义理解能力，同时大幅降低边缘侧计算和存储开销。此外，我们还提出跨节点并行调度机制，实现模型状态加载与解码计算异步协同，提升边缘响应速度。同时，我们研究异构模型层对齐和表示压缩策略，缓解边缘通信负担。

实验结果表明，所提架构在推理时延、系统稳定性和并发处理能力等方面展现出优越适应性和扩展性。

> Emerging intelligent service scenarios in 6G communication impose stringent requirements for low latency, high reliability, and privacy preservation. Generative large language models (LLMs) are gradually becoming key enablers for the integration of semantic communication and computation. However, due to the limited computational resources of edge devices and the increasing complexity of heterogeneous terminal access, existing centralized inference approaches fail to meet the dual demands of response efficiency and data privacy in edge-side inference tasks. To address these challenges, this paper proposes a novel collaborative inference architecture that integrates cloud-based LLMs with edge-deployed small language models (SLMs), enabling dynamic scheduling and sharing of semantic-level intermediate states, and establishing a unified computation-communication paradigm tailored for 6G networks. Specifically, a key-value (KV) cache reuse mechanism is introduced to enhance the semantic understanding of edge models through contextual guidance from the cloud, while significantly reducing edge-side computational and storage overhead. Furthermore, a cross-node parallel scheduling mechanism is proposed to achieve asynchronous coordination between model state loading and decoding computation, thereby improving edge responsiveness. In addition, we investigate layer alignment and representation compression strategies between heterogeneous models to alleviate the communication burden on the edge. Experimental results demonstrate that the proposed architecture exhibits superior adaptability and scalability in terms of inference latency, system stability, and concurrent processing capacity.

[Arxiv](https://arxiv.org/abs/2505.14085)