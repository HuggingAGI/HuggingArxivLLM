# LLMPrism：针对生产环境下的LLM训练平台的黑箱性能诊断工具

发布时间：2025年05月01日

`LLM应用` `人工智能` `云计算`

> LLMPrism: Black-box Performance Diagnosis for Production LLM Training Platforms

# 摘要

> 大型语言模型（LLMs）的广泛应用促使多领域迎来革新，使得LLM训练成为现代企业的核心任务。为应对这一需求，多租户大规模LLM训练平台应运而生，提供专业的LLM训练服务。然而，由于LLM训练过程的复杂性和同步特性，性能问题频发，造成资源的巨大浪费。平台提供商视角的局限性限制了现有分析方法的应用，给LLM训练作业的性能监控和诊断带来了挑战。

本文首次提出了一种创新方法，利用底层网络流数据，基于LLM训练过程中的独特特征，重建作业的训练时间线。我们设计了LLMPrism，这是首个针对LLM训练平台的黑盒性能诊断系统。通过逐步识别LLM训练作业、确定其并行策略并重建训练时间线，LLMPrism实现了对LLM训练系统的非侵入式、轻量级和持续监控。借助这种监控能力，它能够有效诊断潜在的性能问题。

自2024年10月以来，LLMPrism已在我们的大规模生产平台Platform-X上成功部署。评估和部署经验表明，LLMPrism不仅能够实现精准的时间线重建（误差控制在0.3%以内），还能有效诊断各种性能问题，为平台的优化和性能提升提供了有力支持。

> Large Language Models (LLMs) have brought about revolutionary changes in diverse fields, rendering LLM training of utmost importance for modern enterprises. To meet this demand, multi-tenant large-scale LLM training platforms have been built to offer LLM training services. Nevertheless, due to the complexity and synchronous nature of LLM training process, performance issues occur frequently and can result in substantial resource wastage. The limited visibility from the perspective of platform providers impedes existing profiling methods and poses challenges to the monitoring and diagnosis of the performance of LLM training jobs. For the first time, this paper proposes the utilization of underlying network flow data to reconstruct the training timelines of jobs based on the distinct characteristics in the LLM training procedure. We design LLMPrism, the first black-box performance diagnosis system for LLM training platforms. By progressively recognizing LLM training jobs, identifying their parallelism strategies, and reconstructing the training timelines, LLMPrism achieves non-intrusive, lightweight, and continuous monitoring of LLM training systems. Leveraging this monitoring capability, it further effectively diagnoses potential performance issues. Since Oct. 2024, LLMPrism has been deployed on our large-scale production Platform-X, in which the evaluations and deployment experiences demonstrate that LLMPrism can achieve accurate timeline reconstruction with an error within 0.3% and effectively diagnose various performance issues.

[Arxiv](https://arxiv.org/abs/2505.00342)