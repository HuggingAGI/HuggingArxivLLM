# # 大型语言模型的固有特性库：用于检索增强生成
本研究构建了一个大型语言模型的内在机制库，专门用于提升检索增强生成的效果。

发布时间：2025年04月15日

`RAG` `开发者工具`

> A Library of LLM Intrinsics for Retrieval-Augmented Generation

# 摘要

> 在大型语言模型 (LLMs) 的开发者社区中，尚未形成一个类似软件库的清晰模式，以支持大规模协作。即使是常见的检索增强生成 (RAG) 用例，目前也无法基于不同 LLM 提供商一致同意的一组明确 API 来编写 RAG 应用程序。受到编译器内置函数的启发，我们通过引入针对 RAG 的 LLM 内置函数库，提出这一概念的一些要素。LLM 内置函数被定义为可通过一组明确且相对稳定的 API 调用的能力，这些 API 与内置函数本身的实现方式无关。我们库中的内置函数以 LoRA 适配器的形式在 HuggingFace 上发布，并通过一个具有清晰结构化输入输出特性的软件接口在 vLLM 作为推理平台的基础上实现，同时在两个地方都附带了文档和代码。本文详细描述了每个内置函数的预期用途、训练细节和评估，以及多个内置函数的组合使用。

> In the developer community for large language models (LLMs), there is not yet a clean pattern analogous to a software library, to support very large scale collaboration. Even for the commonplace use case of Retrieval-Augmented Generation (RAG), it is not currently possible to write a RAG application against a well-defined set of APIs that are agreed upon by different LLM providers. Inspired by the idea of compiler intrinsics, we propose some elements of such a concept through introducing a library of LLM Intrinsics for RAG. An LLM intrinsic is defined as a capability that can be invoked through a well-defined API that is reasonably stable and independent of how the LLM intrinsic itself is implemented. The intrinsics in our library are released as LoRA adapters on HuggingFace, and through a software interface with clear structured input/output characteristics on top of vLLM as an inference platform, accompanied in both places with documentation and code. This article describes the intended usage, training details, and evaluations for each intrinsic, as well as compositions of multiple intrinsics.

[Arxiv](https://arxiv.org/abs/2504.11704)