# RankLLM：一个基于LLMs的Python重排序工具包

发布时间：2025年05月25日

`LLM应用` `信息检索` `开源工具`

> RankLLM: A Python Package for Reranking with LLMs

# 摘要

> 大型语言模型（LLMs）作为多阶段检索系统中的重排序器，受到了学术界和工业界的广泛关注。这些模型通过精心设计的提示优化检索到的文档列表，常用于基于检索增强生成（RAG）的应用程序中。本文介绍了一个开源的Python重排序包——RankLLM，它具有模块化设计、高度可配置性，并支持在定制化的重排序工作流中使用专有和开源的LLMs。为了提升易用性，RankLLM提供了与Pyserini的可选集成以实现检索功能，并为多阶段管道提供了集成评估。此外，RankLLM包含一个模块，用于详细分析输入提示和LLM响应，针对LLM API的可靠性问题以及混合专家模型（MoE）中的非确定性行为提供解决方案。本文阐述了RankLLM的架构，并提供了详细的分步指南和示例代码。我们复现了RankGPT、LRL、RankVicuna、RankZephyr及其他近期模型的结果。RankLLM与常见的推理框架及多种LLMs实现了兼容，这种兼容性使得已报告的结果能够快速复现，从而加速了研究与实际应用的进程。完整的代码仓库可在rankllm.ai上获取，且该包可通过PyPI进行安装。

> The adoption of large language models (LLMs) as rerankers in multi-stage retrieval systems has gained significant traction in academia and industry. These models refine a candidate list of retrieved documents, often through carefully designed prompts, and are typically used in applications built on retrieval-augmented generation (RAG). This paper introduces RankLLM, an open-source Python package for reranking that is modular, highly configurable, and supports both proprietary and open-source LLMs in customized reranking workflows. To improve usability, RankLLM features optional integration with Pyserini for retrieval and provides integrated evaluation for multi-stage pipelines. Additionally, RankLLM includes a module for detailed analysis of input prompts and LLM responses, addressing reliability concerns with LLM APIs and non-deterministic behavior in Mixture-of-Experts (MoE) models. This paper presents the architecture of RankLLM, along with a detailed step-by-step guide and sample code. We reproduce results from RankGPT, LRL, RankVicuna, RankZephyr, and other recent models. RankLLM integrates with common inference frameworks and a wide range of LLMs. This compatibility allows for quick reproduction of reported results, helping to speed up both research and real-world applications. The complete repository is available at rankllm.ai, and the package can be installed via PyPI.

[Arxiv](https://arxiv.org/abs/2505.19284)