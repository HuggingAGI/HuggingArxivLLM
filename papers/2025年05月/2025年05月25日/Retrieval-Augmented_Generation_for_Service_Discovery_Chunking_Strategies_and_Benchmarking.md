# 基于检索增强生成的服务发现：分块策略与基准测试

发布时间：2025年05月25日

`RAG` `系统集成` `API管理`

> Retrieval-Augmented Generation for Service Discovery: Chunking Strategies and Benchmarking

# 摘要

> 整合多个（子）系统是构建高级信息系统的基石。然而，在动态环境中进行集成，如在设计阶段整合尚未存在的服务，往往面临诸多挑战。传统方法通过注册表提供端点的API文档来解决这一问题。大型语言模型（LLMs）能够根据这些文档自动创建系统集成（如服务组合），但受限于输入标记的长度，尤其是全面的API描述，需要简洁的输入。目前，如何最佳预处理这些API描述尚不明确。在本研究中，我们（i）探讨了检索增强生成（RAG）在端点发现中的应用，以及对实际应用的OpenAPI进行分块处理（即预处理），以减少输入标记长度，同时保留最关键信息。为了进一步减少组合提示的输入标记长度并提升端点检索效果，我们提出（ii）一个发现代理，它仅接收最相关端点的摘要，并按需检索规格细节。我们通过（iii）一个代表跨众多领域和真实世界RestBench基准的新型服务发现基准SOCBench-D，首先评估了RAG在端点发现中的不同分块可能性和参数，以衡量端点检索准确性。随后，我们使用相同的数据集评估发现代理。原型展示了如何成功利用RAG进行端点发现以减少标记数量。实验结果表明，基于端点的方法在预处理中优于 naive 分块方法。依赖代理显著提升了精度，但可能降低召回率，揭示了对进一步推理能力的需求。


> Integrating multiple (sub-)systems is essential to create advanced Information Systems. Difficulties mainly arise when integrating dynamic environments, e.g., the integration at design time of not yet existing services. This has been traditionally addressed using a registry that provides the API documentation of the endpoints. Large Language Models have shown to be capable of automatically creating system integrations (e.g., as service composition) based on this documentation but require concise input due to input oken limitations, especially regarding comprehensive API descriptions. Currently, it is unknown how best to preprocess these API descriptions. In the present work, we (i) analyze the usage of Retrieval Augmented Generation for endpoint discovery and the chunking, i.e., preprocessing, of state-of-practice OpenAPIs to reduce the input oken length while preserving the most relevant information. To further reduce the input token length for the composition prompt and improve endpoint retrieval, we propose (ii) a Discovery Agent that only receives a summary of the most relevant endpoints nd retrieves specification details on demand. We evaluate RAG for endpoint discovery using (iii) a proposed novel service discovery benchmark SOCBench-D representing a general setting across numerous domains and the real-world RestBench enchmark, first, for the different chunking possibilities and parameters measuring the endpoint retrieval accuracy. Then, we assess the Discovery Agent using the same test data set. The prototype shows how to successfully employ RAG for endpoint discovery to reduce the token count. Our experiments show that endpoint-based approaches outperform naive chunking methods for preprocessing. Relying on an agent significantly improves precision while being prone to decrease recall, disclosing the need for further reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2505.19310)