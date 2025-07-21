# # 苹果智能研究院语言模型：2025技术报告

发布时间：2025年07月17日

`LLM应用` `消费电子` `人工智能`

> Apple Intelligence Foundation Language Models: Tech Report 2025

# 摘要

> 我们推出了两款多语言、多模态基础语言模型，赋能 Apple 设备和服务中的智能功能：i 一款30亿参数的设备端模型，通过 KV 缓存共享和 2 位量化感知训练等创新架构优化，专为 Apple 硅片设计；ii 一款基于新型并行轨道专家混合模型（PT-MoE）的可扩展服务器模型，通过轨道并行、专家混合稀疏计算和交错全局-局部注意力机制，在 Apple 的 Private Cloud Compute 平台上实现高质量与成本效益的平衡。两款模型均基于负责任的网络爬取、授权语料库和高质量合成数据构建的大型多语言和多模态数据集训练而成，并通过新的异步平台上的监督微调和强化学习进一步优化。最终的模型支持多种附加语言，同时具备图像理解和工具调用能力。在公共基准测试和人工评估中，无论是服务器模型还是设备端模型，均能与规模相近的开源基线持平或超越。 一个全新的以 Swift 为中心的基础模型框架，提供了引导生成、受限工具调用和 LoRA 适配器微调等功能，让开发者只需几行代码即可轻松集成这些功能。Apple Intelligence 模型的最新进展植根于我们的负责任 AI 方法，包括内容过滤和本地化评估等保障措施，以及我们通过创新如 Private Cloud Compute 保护用户隐私的承诺。

> We introduce two multilingual, multimodal foundation language models that power Apple Intelligence features across Apple devices and services: i a 3B-parameter on-device model optimized for Apple silicon through architectural innovations such as KV-cache sharing and 2-bit quantization-aware training; and ii a scalable server model built on a novel Parallel-Track Mixture-of-Experts PT-MoE transformer that combines track parallelism, mixture-of-experts sparse computation, and interleaved global-local attention to deliver high quality with competitive cost on Apple's Private Cloud Compute platform. Both models are trained on large-scale multilingual and multimodal datasets sourced via responsible web crawling, licensed corpora, and high-quality synthetic data, then further refined with supervised fine-tuning and reinforcement learning on a new asynchronous platform. The resulting models support several additional languages while understanding images and executing tool calls. In public benchmarks and human evaluations, both the server model and the on-device model match or surpass comparably sized open baselines.
  A new Swift-centric Foundation Models framework exposes guided generation, constrained tool calling, and LoRA adapter fine-tuning, allowing developers to integrate these capabilities with a few lines of code. The latest advancements in Apple Intelligence models are grounded in our Responsible AI approach with safeguards like content filtering and locale-specific evaluation, as well as our commitment to protecting our users' privacy with innovations like Private Cloud Compute.

[Arxiv](https://arxiv.org/abs/2507.13575)