# 大型语言模型推理引擎综述：优化与效率的视角分析

发布时间：2025年05月02日

`LLM应用` `LLM优化` `推理引擎`

> A Survey on Inference Engines for Large Language Models: Perspectives on Optimization and Efficiency

# 摘要

> 大型语言模型 (LLMs) 在聊天机器人、代码生成器和搜索引擎中得到了广泛应用。然而，思维链推理、复杂推理和智能体服务等任务通过反复调用模型显著增加了推理成本。为了降低成本，人们采用了并行化、压缩和缓存等优化方法，但多样化的服务需求使得选择合适的优化方法变得困难。最近，专门的 LLM 推理引擎作为将优化方法集成到面向服务的基础设施中的关键组件应运而生。然而，目前尚缺乏对推理引擎的系统性研究。本文对 25 款开源和商业推理引擎进行了全面评估，从易用性、部署难度、通用性支持、可扩展性和吞吐量与延迟感知计算的适用性等方面进行了深入分析。此外，我们通过探究每款推理引擎支持的优化技术，深入探讨了它们的设计目标。同时，我们评估了开源推理引擎的生态系统成熟度，并处理了商业解决方案的性能和成本策略。我们概述了未来的研究方向，包括对复杂 LLM 基础服务的支持、对各类硬件的支持以及安全性增强，为研究人员和开发者在选择和设计优化的 LLM 推理引擎方面提供了实用的指导。此外，我们提供了一个公共仓库，以持续跟踪这一快速发展的领域中的最新进展：https://github.com/sihyeong/Awesome-LLM-Inference-Engine

> Large language models (LLMs) are widely applied in chatbots, code generators, and search engines. Workloads such as chain-of-thought, complex reasoning, and agent services significantly increase the inference cost by invoking the model repeatedly. Optimization methods such as parallelism, compression, and caching have been adopted to reduce costs, but the diverse service requirements make it hard to select the right method. Recently, specialized LLM inference engines have emerged as a key component for integrating the optimization methods into service-oriented infrastructures. However, a systematic study on inference engines is still lacking. This paper provides a comprehensive evaluation of 25 open-source and commercial inference engines. We examine each inference engine in terms of ease-of-use, ease-of-deployment, general-purpose support, scalability, and suitability for throughput- and latency-aware computation. Furthermore, we explore the design goals of each inference engine by investigating the optimization techniques it supports. In addition, we assess the ecosystem maturity of open source inference engines and handle the performance and cost policy of commercial solutions. We outline future research directions that include support for complex LLM-based services, support of various hardware, and enhanced security, offering practical guidance to researchers and developers in selecting and designing optimized LLM inference engines. We also provide a public repository to continually track developments in this fast-evolving field: https://github.com/sihyeong/Awesome-LLM-Inference-Engine

[Arxiv](https://arxiv.org/abs/2505.01658)