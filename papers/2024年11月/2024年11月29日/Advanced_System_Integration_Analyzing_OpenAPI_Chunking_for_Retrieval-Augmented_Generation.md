# 高级系统集成：剖析用于检索增强生成的 OpenAPI 分块

发布时间：2024年11月29日

`RAG` `信息系统` `系统集成`

> Advanced System Integration: Analyzing OpenAPI Chunking for Retrieval-Augmented Generation

# 摘要

> 整合多个（子）系统对于构建高级信息系统（ISs）不可或缺。在信息系统全生命周期中整合动态环境时，困难主要凸显。传统做法是采用注册表来提供系统端点的 API 文档。大型语言模型（LLMs）已证实能够依据此文档自动创建系统集成（比如作为服务组合），但因输入令牌受限，需要简洁输入，尤其对于全面的 API 描述。当下，如何最优地预处理这些 API 描述尚不明确。在本项工作中，我们（i）分析了用于端点发现的检索增强生成（RAG）的运用以及 OpenAPIs 的分块（即预处理），以在减少输入令牌长度的同时保留最关键的信息。为进一步降低组合提示的输入令牌长度并优化端点检索，我们提出（ii）一个发现代理，它仅接收最相关端点的概要，并按需检索详情。我们使用 RestBench 基准评估用于端点发现的 RAG，首先针对不同的分块可能性和参数来衡量端点检索的召回率、精度和 F1 分数。接着，我们用相同的测试集评估发现代理。通过我们的原型，我们展示了如何成功运用 RAG 进行端点发现以减少令牌数量。虽然召回率、精度和 F1 呈现出较高数值，但要检索所有必要端点，仍需进一步研究。我们的实验表明，在预处理方面，基于 LLM 的和特定格式的方法优于简单的分块方法。依靠代理能进一步提升这些结果，因为代理将任务拆分为多个精细的子任务，在令牌数量、精度和 F1 分数上提高了整体 RAG 性能。

> Integrating multiple (sub-)systems is essential to create advanced Information Systems (ISs). Difficulties mainly arise when integrating dynamic environments across the IS lifecycle. A traditional approach is a registry that provides the API documentation of the systems' endpoints. Large Language Models (LLMs) have shown to be capable of automatically creating system integrations (e.g., as service composition) based on this documentation but require concise input due to input token limitations, especially regarding comprehensive API descriptions. Currently, it is unknown how best to preprocess these API descriptions. Within this work, we (i) analyze the usage of Retrieval Augmented Generation (RAG) for endpoint discovery and the chunking, i.e., preprocessing, of OpenAPIs to reduce the input token length while preserving the most relevant information. To further reduce the input token length for the composition prompt and improve endpoint retrieval, we propose (ii) a Discovery Agent that only receives a summary of the most relevant endpoints and retrieves details on demand. We evaluate RAG for endpoint discovery using the RestBench benchmark, first, for the different chunking possibilities and parameters measuring the endpoint retrieval recall, precision, and F1 score. Then, we assess the Discovery Agent using the same test set. With our prototype, we demonstrate how to successfully employ RAG for endpoint discovery to reduce the token count. While revealing high values for recall, precision, and F1, further research is necessary to retrieve all requisite endpoints. Our experiments show that for preprocessing, LLM-based and format-specific approaches outperform naïve chunking methods. Relying on an agent further enhances these results as the agent splits the tasks into multiple fine granular subtasks, improving the overall RAG performance in the token count, precision, and F1 score.

[Arxiv](https://arxiv.org/abs/2411.19804)