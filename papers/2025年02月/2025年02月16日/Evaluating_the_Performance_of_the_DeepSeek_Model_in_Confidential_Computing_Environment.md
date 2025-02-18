# 在 confidential 计算环境中评估 DeepSeek 模型的性能表现

发布时间：2025年02月16日

`LLM应用` `可信计算` `数据隐私`

> Evaluating the Performance of the DeepSeek Model in Confidential Computing Environment

# 摘要

> 随着大型语言模型（LLMs）在云环境中的广泛应用，模型保密性和数据隐私等关键安全性问题日益凸显。可信计算通过可信执行环境（TEEs）提供了解决这些挑战的潜在方案。然而，现有的主要基于CPU的TEE实现难以高效支持LLM推理与训练的资源密集型特性。本研究首次对DeepSeek模型在英特尔信任域扩展（TDX）技术支持下的可信计算环境进行了性能评估。我们对DeepSeek模型在仅CPU、CPU-GPU混合以及基于TEE的三种实现方式下的表现进行了全面基准测试。研究发现，对于较小的参数集（如DeepSeek-R1-1.5B），TDX实现相较于CPU版本在安全环境下的计算性能更优。这一结果表明，在资源受限的系统中，仍有可能实现高效且安全的LLM模型部署。整体来看，GPU与CPU的性能比平均为12，且模型规模越小，该比率越低。此外，我们还为优化CPU-GPU可信计算方案提供了基础性的见解与指导，助力实现可扩展且安全的AI部署。我们的研究发现为隐私保护AI技术的发展注入了新动力，为在可信计算环境中实现高效且安全的LLM推理奠定了坚实基础。

> The increasing adoption of Large Language Models (LLMs) in cloud environments raises critical security concerns, particularly regarding model confidentiality and data privacy. Confidential computing, enabled by Trusted Execution Environments (TEEs), offers a promising solution to mitigate these risks. However, existing TEE implementations, primarily CPU-based, struggle to efficiently support the resource-intensive nature of LLM inference and training. In this work, we present the first evaluation of the DeepSeek model within a TEE-enabled confidential computing environment, specifically utilizing Intel Trust Domain Extensions (TDX). Our study benchmarks DeepSeek's performance across CPU-only, CPU-GPU hybrid, and TEE-based implementations. For smaller parameter sets, such as DeepSeek-R1-1.5B, the TDX implementation outperforms the CPU version in executing computations within a secure environment. It highlights the potential for efficiently deploying LLM models on resource-constrained systems while ensuring security. The overall GPU-to-CPU performance ratio averages 12 across different model sizes, with smaller models exhibiting a lower ratio. Additionally, we provide foundational insights and guidance on optimizing CPU-GPU confidential computing solutions for scalable and secure AI deployments. Our findings contribute to the advancement of privacy-preserving AI, paving the way for efficient and secure LLM inference in confidential computing environments.

[Arxiv](https://arxiv.org/abs/2502.11347)