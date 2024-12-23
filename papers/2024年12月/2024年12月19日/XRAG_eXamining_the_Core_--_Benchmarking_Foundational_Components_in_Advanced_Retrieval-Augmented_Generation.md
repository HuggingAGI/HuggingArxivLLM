# XRAG: 探究核心——为高级检索增强生成中的基础组件设立基准

发布时间：2024年12月19日

`RAG` `人工智能`

> XRAG: eXamining the Core -- Benchmarking Foundational Components in Advanced Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）将相关数据的检索与大型语言模型（LLMs）的生成能力相结合，确保生成的内容不仅与上下文相关，而且准确且新颖。我们推出了 XRAG，这是一个开源的模块化代码库，有助于对先进 RAG 模块的基础组件性能进行全面评估。这些组件被系统地划分为四个核心阶段：预检索、检索、检索后和生成。我们在重新配置的数据集上对其进行系统分析，为其有效性提供了全面的基准。鉴于 RAG 系统越来越复杂，我们强调了找出 RAG 模块潜在故障点的必要性。我们制定了一系列实验方法和诊断测试协议，来剖析 RAG 模块工程中固有的故障点。随后，我们提供了定制的解决方案，旨在加强验证过程并提升这些模块的整体性能。我们的工作全面评估了 RAG 系统中核心先进组件的性能，为常见故障点的优化提供了思路。

> Retrieval-augmented generation (RAG) synergizes the retrieval of pertinent data with the generative capabilities of Large Language Models (LLMs), ensuring that the generated output is not only contextually relevant but also accurate and current.We introduce XRAG, an open-source, modular codebase that facilitates exhaustive evaluation of the performance of foundational components of advanced RAG modules. These components are systematically categorized into four core phases: pre-retrieval, retrieval, post-retrieval, and generation. We systematically analyse them across reconfigured datasets, providing a comprehensive benchmark for their effectiveness. Given the escalating complexity of RAG systems, we underscore the necessity of identifying potential failure points of RAG modules. We formulate a suite of experimental methodologies and diagnostic testing protocols to dissect the failure points inherent in the engineering of RAG modules. Subsequently, we proffer bespoke solutions that are designed to augment the validation processes and bolster the overall performance of these modules. Our work thoroughly evaluates the performance of core advanced components in RAG systems, providing insights into optimizations for prevalent failure points.

[Arxiv](https://arxiv.org/abs/2412.15529)