# # 分布式检索增强生成式模型

发布时间：2025年05月01日

`RAG` `分布式系统`

> Distributed Retrieval-Augmented Generation

# 摘要

> 随着大型语言模型 (LLMs) 在边缘设备上的广泛应用，检索增强生成 (RAG) 作为一种通过整合外部知识来解决事实缺失和幻觉问题的方案，正逐渐受到重视。然而，集中式 RAG 架构在数据隐私和可扩展性方面面临重大挑战。例如，智能医疗健康服务通常依赖收集敏感的患者数据并构建集中式知识库来提供更好的诊断和治疗建议，但隐私问题严重阻碍了这一过程。此外，维护全面且持续更新的知识库成本高昂，尤其是在应对区域疫情和快速变异的病毒时。为了解决这些问题，本文提出了分布式检索增强生成 (DRAG)，这是一种通过消除对集中式知识库的需求并将数据控制权归还给所有者来改进数据隐私的新颖框架。DRAG 集成了主题感知随机游走 (TARW) 算法，该算法利用 LLMs 提取查询主题并在点对点网络中促进有针对性的对等发现，从而实现去中心化环境中的高效知识检索。在三个多样化数据集和 LLMs 上进行的广泛实验表明，与泛滥式方法相比，DRAG 采用 TARW 仅需一半的消息量即可实现接近集中式 RAG 的性能。代码可在 https://github.com/xuchenhao001/DRAG 获取。

> As large language models (LLMs) become increasingly adopted on edge devices, Retrieval-Augmented Generation (RAG) is gaining prominence as a solution to address factual deficiencies and hallucinations by integrating external knowledge. However, centralized RAG architectures face significant challenges in data privacy and scalability. For instance, smart healthcare services often rely on collecting sensitive patient data and building a centralized knowledge base to provide better diagnosis and treatment advice, while privacy concerns significantly impede this process. Besides, maintaining a comprehensive and continuously updated knowledge base is costly, particularly in response to regional epidemics and rapidly mutating viruses. To address these challenges, this paper introduces Distributed Retrieval-Augmented Generation (DRAG), a novel framework that improves data privacy by eliminating the need for a centralized knowledge base and restoring data control to owners. DRAG incorporates a Topic-Aware Random Walk (TARW) algorithm that leverages LLMs to extract query topics and facilitate targeted peer discovery within a peer-to-peer network, enabling efficient knowledge retrieval in decentralized environments. Extensive experiments across three diverse datasets and LLMs demonstrate that DRAG with TARW achieves near-centralized RAG performance by using half as many messages as flooding. The code is available at https://github.com/xuchenhao001/DRAG.

[Arxiv](https://arxiv.org/abs/2505.00443)