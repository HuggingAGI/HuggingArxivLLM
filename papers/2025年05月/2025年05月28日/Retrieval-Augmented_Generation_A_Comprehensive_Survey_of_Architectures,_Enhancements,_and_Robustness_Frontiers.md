# 检索增强生成：架构、增强方法及鲁棒性前沿的系统性综述
本综述全面探讨了检索增强生成技术，涵盖了从模型架构到增强方法，再到鲁棒性前沿的各个层面。

发布时间：2025年05月28日

`RAG` `问答系统`

> Retrieval-Augmented Generation: A Comprehensive Survey of Architectures, Enhancements, and Robustness Frontiers

# 摘要

> 检索增强生成（RAG）作为一种强大的范式出现，通过在推理过程中引入外部检索证据来提升大型语言模型（LLMs）的表现。虽然RAG解决了参数化知识存储在事实一致性、领域灵活性等方面的局限性，但它也带来了新的挑战，涉及检索质量、事实依据的准确性、流水线效率以及面对噪声或对抗输入时的鲁棒性。本综述旨在全面整合近期在RAG系统方面的进展，提供了一个分类体系，将架构划分为以检索器为中心、以生成器为中心、混合型以及注重鲁棒性的设计。我们系统性地分析了在检索优化、上下文过滤、解码控制以及效率提升方面的改进，并通过在短文本和多跳问答任务上的性能对比分析予以支持。此外，我们还回顾了最新的评估框架和基准测试，重点介绍了检索感知评估、鲁棒性测试以及联合检索设置的发展趋势。我们的分析揭示了在检索精确度与生成灵活性、效率与忠实度、模块化与协调性之间存在的反复权衡。最后，我们指出了开放的挑战和未来的研究方向，包括自适应检索架构、实时检索集成、基于多跳证据的结构化推理以及隐私保护的检索机制。本次综述旨在整合RAG研究领域的现有知识，并为下一代检索增强语言建模系统奠定基础。

> Retrieval-Augmented Generation (RAG) has emerged as a powerful paradigm to enhance large language models (LLMs) by conditioning generation on external evidence retrieved at inference time. While RAG addresses critical limitations of parametric knowledge storage-such as factual inconsistency and domain inflexibility-it introduces new challenges in retrieval quality, grounding fidelity, pipeline efficiency, and robustness against noisy or adversarial inputs. This survey provides a comprehensive synthesis of recent advances in RAG systems, offering a taxonomy that categorizes architectures into retriever-centric, generator-centric, hybrid, and robustness-oriented designs. We systematically analyze enhancements across retrieval optimization, context filtering, decoding control, and efficiency improvements, supported by comparative performance analyses on short-form and multi-hop question answering tasks. Furthermore, we review state-of-the-art evaluation frameworks and benchmarks, highlighting trends in retrieval-aware evaluation, robustness testing, and federated retrieval settings. Our analysis reveals recurring trade-offs between retrieval precision and generation flexibility, efficiency and faithfulness, and modularity and coordination. We conclude by identifying open challenges and future research directions, including adaptive retrieval architectures, real-time retrieval integration, structured reasoning over multi-hop evidence, and privacy-preserving retrieval mechanisms. This survey aims to consolidate current knowledge in RAG research and serve as a foundation for the next generation of retrieval-augmented language modeling systems.

[Arxiv](https://arxiv.org/abs/2506.00054)