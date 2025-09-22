# LiteLong：面向LLMs的资源高效长上下文数据合成

发布时间：2025年09月19日

`LLM应用` `基础理论`

> LiteLong: Resource-Efficient Long-Context Data Synthesis for LLMs

# 摘要

> 高质量长上下文数据是训练能处理海量文档的大型语言模型（LLMs）的关键，然而现有基于相关性聚合的合成方法却受困于计算效率问题。为此，我们提出LiteLong——一种资源高效的长上下文数据合成方案，它借助结构化主题组织与多智能体辩论实现。该方法首先利用BISAC图书分类系统构建全面的层级主题体系，随后通过多LLM辩论机制在体系内生成多样化、高质量的主题。针对每个主题，我们采用轻量级BM25检索获取相关文档，并拼接为128K-token的训练样本。在HELMET和Ruler基准测试中，LiteLong不仅展现出具有竞争力的长上下文性能，还能与其他长依赖增强方法无缝集成。通过降低计算与数据工程成本，LiteLong让高质量长上下文数据合成更易实现，为长上下文语言训练的深入研究铺平了道路。

> High-quality long-context data is essential for training large language models (LLMs) capable of processing extensive documents, yet existing synthesis approaches using relevance-based aggregation face challenges of computational efficiency. We present LiteLong, a resource-efficient method for synthesizing long-context data through structured topic organization and multi-agent debate. Our approach leverages the BISAC book classification system to provide a comprehensive hierarchical topic organization, and then employs a debate mechanism with multiple LLMs to generate diverse, high-quality topics within this structure. For each topic, we use lightweight BM25 retrieval to obtain relevant documents and concatenate them into 128K-token training samples. Experiments on HELMET and Ruler benchmarks demonstrate that LiteLong achieves competitive long-context performance and can seamlessly integrate with other long-dependency enhancement methods. LiteLong makes high-quality long-context data synthesis more accessible by reducing both computational and data engineering costs, facilitating further research in long-context language training.

[Arxiv](https://arxiv.org/abs/2509.15568)