# Fed Nano：轻量化联邦微调预训练多模态大语言模型的研究探索

发布时间：2025年06月12日

`LLM应用` `人工智能` `隐私保护`

> FedNano: Toward Lightweight Federated Tuning for Pretrained Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在多模态推理和跨模态检索等领域表现优异，但因其数据分布和隐私要求，在实际应用中面临诸多部署挑战。联邦学习（FL）通过不集中数据的方式实现模型协作训练，为这一难题提供了解决方案。然而，MLLMs的联邦学习实现面临诸多难题，包括计算需求高、客户端容量有限、通信成本高昂以及数据异构等问题。现有FL方法假设客户端部署完整模型，这一假设在面对大规模MLLMs时难以实现，因其体积庞大且通信需求极高。为解决这些问题，我们提出了FedNano，首个将LLM集中部署在服务器端的FL框架，并引入了NanoEdge这一轻量级客户端适应模块。NanoEdge通过模态特定编码器、连接器和具备低秩适应的可训练NanoAdapters实现高效适配。这一设计彻底避免了客户端部署LLM的需求，将客户端存储需求降低95%，通信开销仅占模型参数的0.01%。通过仅传输紧凑的NanoAdapter更新，FedNano在满足隐私保护的同时，有效处理异构数据和资源限制。实验结果表明，FedNano显著优于现有FL基线，成功弥合了MLLM规模与FL可行性之间的鸿沟，为构建可扩展的去中心化多模态AI系统铺平了道路。

> Multimodal Large Language Models (MLLMs) excel in tasks like multimodal reasoning and cross-modal retrieval but face deployment challenges in real-world scenarios due to distributed multimodal data and strict privacy requirements. Federated Learning (FL) offers a solution by enabling collaborative model training without centralizing data. However, realizing FL for MLLMs presents significant challenges, including high computational demands, limited client capacity, substantial communication costs, and heterogeneous client data. Existing FL methods assume client-side deployment of full models, an assumption that breaks down for large-scale MLLMs due to their massive size and communication demands. To address these limitations, we propose FedNano, the first FL framework that centralizes the LLM on the server while introducing NanoEdge, a lightweight module for client-specific adaptation. NanoEdge employs modality-specific encoders, connectors, and trainable NanoAdapters with low-rank adaptation. This design eliminates the need to deploy LLM on clients, reducing client-side storage by 95%, and limiting communication overhead to only 0.01% of the model parameters. By transmitting only compact NanoAdapter updates, FedNano handles heterogeneous client data and resource constraints while preserving privacy. Experiments demonstrate that FedNano outperforms prior FL baselines, bridging the gap between MLLM scale and FL feasibility, and enabling scalable, decentralized multimodal AI systems.

[Arxiv](https://arxiv.org/abs/2506.14824)