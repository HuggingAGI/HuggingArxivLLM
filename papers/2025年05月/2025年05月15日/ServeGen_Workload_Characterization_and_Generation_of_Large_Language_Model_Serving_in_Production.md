# # ServeGen：大规模语言模型服务在生产环境中的工作负载特征分析与生成

发布时间：2025年05月15日

`LLM应用` `云计算`

> ServeGen: Workload Characterization and Generation of Large Language Model Serving in Production

# 摘要

> 随着大型语言模型 (LLMs) 的广泛应用，处理 LLM 推理请求已成为一项日益重要的任务，吸引了活跃的研究进展。实际工作负载在此过程中扮演着至关重要的角色：它们对于激励和评估服务技术与系统至关重要。然而，由于缺乏全面的工作负载特征分析，对真实世界 LLM 服务工作负载的理解仍然有限。先前的分析在规模和范围上仍显不足，因此未能完全捕捉到复杂的工作负载特性。
    
    在本文中，我们通过深入分析从我们全球云推理服务中收集的 LLM 服务工作负载，涵盖不仅包括语言模型，还包括新兴的多模态和推理模型，填补了这一空白，并在每种情况下揭示了重要的新发现。此外，基于我们的发现，我们提出了 ServeGen，这是一个通过按客户端组合生成现实 LLM 服务工作负载的原理性框架。生产环境中的实际用例验证了与简单的 workload 生成方法相比，ServeGen 避免了 50% 的配置不足，展示了 ServeGen 在性能基准测试中的优势。我们将开源 ServeGen 以促进未来的研究。

> With the widespread adoption of Large Language Models (LLMs), serving LLM inference requests has become an increasingly important task, attracting active research advancements. Practical workloads play an essential role in this process: they are critical for motivating and benchmarking serving techniques and systems. However, the existing understanding of real-world LLM serving workloads is limited due to the lack of a comprehensive workload characterization. Prior analyses remain insufficient in scale and scope, thus failing to fully capture intricate workload characteristics.
  In this paper, we fill the gap with an in-depth characterization of LLM serving workloads collected from our worldwide cloud inference serving service, covering not only language models but also emerging multimodal and reasoning models, and unveiling important new findings in each case. Moreover, based on our findings, we propose ServeGen, a principled framework for generating realistic LLM serving workloads by composing them on a per-client basis. A practical use case in production validates that ServeGen avoids 50% under-provisioning compared to naive workload generation, demonstrating ServeGen's advantage in performance benchmarking. We will open-source ServeGen to foster future research.

[Arxiv](https://arxiv.org/abs/2505.09999)