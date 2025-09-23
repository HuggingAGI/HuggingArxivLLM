# AttnComp：注意力引导的自适应上下文压缩面向检索增强生成

发布时间：2025年09月22日

`RAG` `基础理论`

> AttnComp: Attention-Guided Adaptive Context Compression for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合外部上下文提升了大型语言模型（LLMs）的事实准确性，但常因检索到无关内容而降低效果。上下文压缩通过在LLM生成前过滤掉上下文中的无关信息来解决这一问题。然而，现有方法难以针对不同上下文自适应调整压缩率、维持低延迟，也无法有效跨多文档整合信息。为解决这些局限，我们提出了AttnComp——一个自适应、高效且具备上下文感知能力的压缩框架。AttnComp借助LLMs的注意力机制识别相关信息，并采用Top-P压缩算法保留累积注意力权重超过预设阈值的最小文档集。除压缩功能外，AttnComp还通过评估检索内容的整体相关性来估计响应置信度，帮助用户判断响应的可靠性。实验结果显示，AttnComp性能超过现有压缩方法和未压缩基线，在实现高压缩率和低延迟的同时，还能提升准确性。

> Retrieval-augmented generation improves the factual accuracy of Large Language Models (LLMs) by incorporating external context, but often suffers from irrelevant retrieved content that hinders effectiveness. Context compression addresses this issue by filtering out irrelevant information from context before LLM generation. However, existing methods struggle to adaptively adjust compression rates for different context, maintain low latency and integrate information across multiple documents. To overcome these limitations, We introduce AttnComp, an adaptive, efficient and context-aware compression framework. By leveraging the attention mechanism of LLMs to identify relevant information, AttnComp employs a Top-P compression algorithm to retain the minimal set of documents whose cumulative attention weights exceeds a predefined threshold. In addition to compression, AttnComp estimates response confidence by assessing the overall relevance of the retrieved content, enabling users to gauge response reliability. Experiments demonstrate that AttnComp outperforms existing compression methods and uncompressed baselines, achieving higher accuracy with substantial compression rates and lower latency.

[Arxiv](https://arxiv.org/abs/2509.17486)