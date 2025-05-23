# InfoDeepSeek：智能检索基准测试，应用于检索增强生成

发布时间：2025年05月21日

`RAG` `信息检索` `人工智能`

> InfoDeepSeek: Benchmarking Agentic Information Seeking for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过将检索到的信息融入回答，显著提升了大型语言模型（LLMs）的能力。作为一种新兴范式，Agentic RAG通过在信息检索过程中引入自主的LLM代理，进一步优化了这一过程。然而，现有的基准测试在评估此类系统时存在局限性，因为它们局限于静态的检索环境，使用固定且有限的语料库以及简单的查询，无法激发真正的自主行为。此外，它们的评估协议通过预定义的黄金文档集来衡量信息检索的有效性，这使得它们不适合评估开放性和动态性的真实网络环境。为了解决这一问题，我们提出了InfoDeepSeek，这是一个全新的基准，专为评估真实动态网络环境中的自主信息检索而设计。我们提出了一种系统化的方法来构建符合确定性、难度和多样性标准的具有挑战性的查询。基于此，我们开发了第一个专门针对动态自主信息检索的评估框架，其中包括关于信息检索结果准确性、实用性和简洁性的细粒度指标。通过在不同LLMs、搜索引擎和问题类型上的广泛实验，InfoDeepSeek揭示了细微的代理行为，并为未来的研究提供了可操作的见解。

> Retrieval-Augmented Generation (RAG) enhances large language models (LLMs) by grounding responses with retrieved information. As an emerging paradigm, Agentic RAG further enhances this process by introducing autonomous LLM agents into the information seeking process. However, existing benchmarks fall short in evaluating such systems, as they are confined to a static retrieval environment with a fixed, limited corpus} and simple queries that fail to elicit agentic behavior. Moreover, their evaluation protocols assess information seeking effectiveness by pre-defined gold sets of documents, making them unsuitable for the open-ended and dynamic nature of real-world web environments. To bridge this gap, we present InfoDeepSeek, a new benchmark with challenging questions designed for assessing agentic information seeking in real-world, dynamic web environments. We propose a systematic methodology for constructing challenging queries satisfying the criteria of determinacy, difficulty, and diversity. Based on this, we develop the first evaluation framework tailored to dynamic agentic information seeking, including fine-grained metrics about the accuracy, utility, and compactness of information seeking outcomes. Through extensive experiments across LLMs, search engines, and question types, InfoDeepSeek reveals nuanced agent behaviors and offers actionable insights for future research.

[Arxiv](https://arxiv.org/abs/2505.15872)