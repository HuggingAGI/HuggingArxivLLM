# # 推理动力学  
通过结构化能力与知识剖析实现跨LLM的高效路由

发布时间：2025年05月22日

`LLM应用` `人工智能`

> INFERENCEDYNAMICS: Efficient Routing Across LLMs through Structured Capability and Knowledge Profiling

# 摘要

> 大型语言模型 (LLM) 路由是一项关键的技术，用于在多样化的 LLM 生态中进行导航，旨在根据用户查询的领域选择表现最佳的 LLM，同时高效管理计算资源。然而，现有的路由方法在处理大量专业 LLM 时，往往面临扩展性不足的问题，或者在适应模型范围扩展和能力领域演变方面显得不够灵活。为了解决这些挑战，我们提出了 InferenceDynamics，这是一个通过建模模型的能力和知识来实现的灵活且可扩展的多维路由框架。我们在全面的 RouteMix 数据集上运行该框架，并通过现代基准测试（包括 MMLU-Pro、GPQA、BigGenBench 和 LiveBench）在组级路由中展示了其有效性和通用性，证明了它能够识别并利用给定任务中的顶级表现模型，从而实现更优的结果和资源的高效利用。InferenceDynamics 的广泛应用能够使用户充分挖掘 LLM 生态系统的专业潜力，我们的代码将公开发布，以鼓励进一步的研究。

> Large Language Model (LLM) routing is a pivotal technique for navigating a diverse landscape of LLMs, aiming to select the best-performing LLMs tailored to the domains of user queries, while managing computational resources. However, current routing approaches often face limitations in scalability when dealing with a large pool of specialized LLMs, or in their adaptability to extending model scope and evolving capability domains. To overcome those challenges, we propose InferenceDynamics, a flexible and scalable multi-dimensional routing framework by modeling the capability and knowledge of models. We operate it on our comprehensive dataset RouteMix, and demonstrate its effectiveness and generalizability in group-level routing using modern benchmarks including MMLU-Pro, GPQA, BigGenBench, and LiveBench, showcasing its ability to identify and leverage top-performing models for given tasks, leading to superior outcomes with efficient resource utilization. The broader adoption of Inference Dynamics can empower users to harness the full specialized potential of the LLM ecosystem, and our code will be made publicly available to encourage further research.

[Arxiv](https://arxiv.org/abs/2505.16303)