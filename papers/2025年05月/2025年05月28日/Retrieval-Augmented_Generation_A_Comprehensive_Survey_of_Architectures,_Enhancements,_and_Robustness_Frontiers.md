# 检索增强生成：架构、改进与稳健性前沿的深度解析

发布时间：2025年05月28日

`RAG` `问答系统`

> Retrieval-Augmented Generation: A Comprehensive Survey of Architectures, Enhancements, and Robustness Frontiers

# 摘要

> 检索增强生成（RAG）作为一种强大的范式，通过在推理时基于外部检索证据来增强大型语言模型（LLMs）的生成能力。虽然RAG解决了参数化知识存储的关键限制，如事实不一致和领域 rigidity，但它也带来了新的挑战，包括检索质量、生成依据的忠实性、管道效率以及对噪声或对抗性输入的鲁棒性。本调查全面综述了近期RAG系统的研究进展，提供了一种分类法，将架构划分为以检索器为中心、以生成器为中心、混合型和以鲁棒性为导向的设计。我们系统性地分析了在检索优化、上下文过滤、解码控制和效率提升方面的改进，并通过在短文本和多跳问答任务上的比较性能分析提供支持。此外，我们回顾了最新的评估框架和基准测试，强调了检索感知评估、鲁棒性测试和联合检索设置的趋势。我们的分析揭示了检索精度与生成灵活性、效率与忠实性、模块化与协调性之间的反复权衡。最后，我们指出了开放性挑战和未来研究方向，包括自适应检索架构、实时检索集成、多跳证据上的结构化推理以及隐私保护的检索机制。本次调查旨在整合RAG研究的现有知识，并为下一代检索增强语言建模系统奠定基础。

> Retrieval-Augmented Generation (RAG) has emerged as a powerful paradigm to enhance large language models (LLMs) by conditioning generation on external evidence retrieved at inference time. While RAG addresses critical limitations of parametric knowledge storage-such as factual inconsistency and domain inflexibility-it introduces new challenges in retrieval quality, grounding fidelity, pipeline efficiency, and robustness against noisy or adversarial inputs. This survey provides a comprehensive synthesis of recent advances in RAG systems, offering a taxonomy that categorizes architectures into retriever-centric, generator-centric, hybrid, and robustness-oriented designs. We systematically analyze enhancements across retrieval optimization, context filtering, decoding control, and efficiency improvements, supported by comparative performance analyses on short-form and multi-hop question answering tasks. Furthermore, we review state-of-the-art evaluation frameworks and benchmarks, highlighting trends in retrieval-aware evaluation, robustness testing, and federated retrieval settings. Our analysis reveals recurring trade-offs between retrieval precision and generation flexibility, efficiency and faithfulness, and modularity and coordination. We conclude by identifying open challenges and future research directions, including adaptive retrieval architectures, real-time retrieval integration, structured reasoning over multi-hop evidence, and privacy-preserving retrieval mechanisms. This survey aims to consolidate current knowledge in RAG research and serve as a foundation for the next generation of retrieval-augmented language modeling systems.

[Arxiv](https://arxiv.org/abs/2506.00054)