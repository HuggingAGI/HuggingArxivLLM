# ComposeRAG：模块化可组合的RAG框架，实现基于语料库的多跳问答

发布时间：2025年05月30日

`RAG` `问答系统` `信息检索`

> ComposeRAG: A Modular and Composable RAG for Corpus-Grounded Multi-Hop Question Answering

# 摘要

> 检索增强生成（RAG）系统正在变得越来越多样化，但许多系统仍面临一个共同问题：它们将查询改写、检索、推理和验证等功能紧密耦合在一起，形成了一个难以拆解的“大块头”。这种设计不仅让系统的可解释性打了折扣，也让系统性评估和针对性优化变得困难，尤其是在处理复杂的多跳问答任务时。今天，我们很高兴向大家介绍ComposeRAG——一种全新的模块化抽象方法。ComposeRAG将传统的RAG流水线拆解成多个原子化的、可组合的模块。每个模块，比如问题分解、查询改写、检索决策和答案验证，都像一个独立的“小引擎”，可以单独实现、升级和分析。为了增强系统在多步推理中的鲁棒性，ComposeRAG还内置了一个自我反思机制。当验证环节发现问题时，它会自动返回去重新审视并优化之前的步骤，就像是一个不断优化自己的聪明助手。在四个具有挑战性的多跳问答基准测试中，ComposeRAG的表现令人瞩目：它不仅在准确性和事实依据的忠实度方面超越了强大的基线模型，还在相同的检索条件下，比基于微调的方法提升了高达15%的准确率，比专门用于推理的流水线提升了5%的性能。更重要的是，ComposeRAG在增强事实依据方面表现尤为突出。通过以验证为先的设计理念，在低质量检索环境中，它将无根据的答案减少了10%以上；即使在使用高质量语料库的情况下，也减少了约3%的无根据答案。通过全面的消融研究，我们验证了ComposeRAG的模块化架构确实具有明确且累积的贡献，每个组件都发挥了独特的作用。这些发现充分展示了ComposeRAG在实现灵活、透明、可扩展和高性能的多跳推理方面的潜力，同时显著提升了事实依据和可解释性。无论是在技术突破还是实际应用中，ComposeRAG都为未来的研究和开发提供了重要的参考和方向。

> Retrieval-Augmented Generation (RAG) systems are increasingly diverse, yet many suffer from monolithic designs that tightly couple core functions like query reformulation, retrieval, reasoning, and verification. This limits their interpretability, systematic evaluation, and targeted improvement, especially for complex multi-hop question answering. We introduce ComposeRAG, a novel modular abstraction that decomposes RAG pipelines into atomic, composable modules. Each module, such as Question Decomposition, Query Rewriting, Retrieval Decision, and Answer Verification, acts as a parameterized transformation on structured inputs/outputs, allowing independent implementation, upgrade, and analysis. To enhance robustness against errors in multi-step reasoning, ComposeRAG incorporates a self-reflection mechanism that iteratively revisits and refines earlier steps upon verification failure. Evaluated on four challenging multi-hop QA benchmarks, ComposeRAG consistently outperforms strong baselines in both accuracy and grounding fidelity. Specifically, it achieves up to a 15% accuracy improvement over fine-tuning-based methods and up to a 5% gain over reasoning-specialized pipelines under identical retrieval conditions. Crucially, ComposeRAG significantly enhances grounding: its verification-first design reduces ungrounded answers by over 10% in low-quality retrieval settings, and by approximately 3% even with strong corpora. Comprehensive ablation studies validate the modular architecture, demonstrating distinct and additive contributions from each component. These findings underscore ComposeRAG's capacity to deliver flexible, transparent, scalable, and high-performing multi-hop reasoning with improved grounding and interpretability.

[Arxiv](https://arxiv.org/abs/2506.00232)