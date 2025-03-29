# Alipay 搜索中基于 LLM 的生成式检索幻觉缓解方法研究

发布时间：2025年03月26日

`LLM应用` `搜索引擎`

> Alleviating LLM-based Generative Retrieval Hallucination in Alipay Search

# 摘要

> 生成式检索（Generative Retrieval, GR）的出现彻底改变了文档检索领域，这一技术正逐渐被行业采用。然而，基于LLM的GR虽然优势显著，却面临幻觉问题，在某些情况下生成的文档与查询无关，这严重挑战了其在实际应用中的可信度。为此，我们提出了一种优化的GR框架，旨在缓解检索幻觉问题。该框架在模型训练中集成了知识蒸馏推理，并引入决策代理以进一步提升检索精度。具体而言，我们利用LLMs评估并推理GR检索到的查询-文档（q-d）对，然后将推理数据作为迁移知识蒸馏到GR模型中。此外，我们还引入决策代理作为后处理，通过检索模型扩展GR检索到的文档，并从多角度筛选出最相关的文档作为最终的生成式检索结果。我们的框架在真实世界数据集上的大量离线实验，以及支付宝平台上基金搜索和保险搜索的在线A/B测试，均证明了其在提升搜索质量和转化率方面的优越性和有效性。

> Generative retrieval (GR) has revolutionized document retrieval with the advent of large language models (LLMs), and LLM-based GR is gradually being adopted by the industry. Despite its remarkable advantages and potential, LLM-based GR suffers from hallucination and generates documents that are irrelevant to the query in some instances, severely challenging its credibility in practical applications. We thereby propose an optimized GR framework designed to alleviate retrieval hallucination, which integrates knowledge distillation reasoning in model training and incorporate decision agent to further improve retrieval precision. Specifically, we employ LLMs to assess and reason GR retrieved query-document (q-d) pairs, and then distill the reasoning data as transferred knowledge to the GR model. Moreover, we utilize a decision agent as post-processing to extend the GR retrieved documents through retrieval model and select the most relevant ones from multi perspectives as the final generative retrieval result. Extensive offline experiments on real-world datasets and online A/B tests on Fund Search and Insurance Search in Alipay demonstrate our framework's superiority and effectiveness in improving search quality and conversion gains.

[Arxiv](https://arxiv.org/abs/2503.21098)