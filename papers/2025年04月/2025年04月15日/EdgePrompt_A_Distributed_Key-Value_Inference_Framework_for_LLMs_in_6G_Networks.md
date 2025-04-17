# EdgePrompt：为6G网络中的大型语言模型打造的分布式键值推理框架

发布时间：2025年04月15日

`LLM应用`

> EdgePrompt: A Distributed Key-Value Inference Framework for LLMs in 6G Networks

# 摘要

> 随着6G网络的演进，大语言模型（LLMs）正逐步融入6G基础设施，助力网络管理和智能化。然而，传统LLMs架构难以满足6G对时延和安全性的严苛要求，尤其是序列长度增加带来的复杂度问题。本文提出了一种基于分层注意力拼接机制的云边协同框架——Edge-Prompt。该框架通过分布式键值（KV）对优化技术加速推理，灵活适应网络环境。同时，为降低数据泄露风险，Edge-Prompt采用隐私保护策略，在处理过程中隔离敏感信息。实验结果表明，EdgePrompt显著提升了推理吞吐量，降低了时延，为6G环境下LLMs的部署提供了可靠解决方案。

> As sixth-generation (6G) networks advance, large language models (LLMs) are increasingly integrated into 6G infrastructure to enhance network management and intelligence. However, traditional LLMs architecture struggle to meet the stringent latency and security requirements of 6G, especially as the increasing in sequence length leads to greater task complexity. This paper proposes Edge-Prompt, a cloud-edge collaborative framework based on a hierarchical attention splicing mechanism. EdgePrompt employs distributed key-value (KV) pair optimization techniques to accelerate inference and adapt to network conditions. Additionally, to reduce the risk of data leakage, EdgePrompt incorporates a privacy preserving strategy by isolating sensitive information during processing. Experiments on public dataset show that EdgePrompt effectively improves the inference throughput and reduces the latency, which provides a reliable solution for LLMs deployment in 6G environments.

[Arxiv](https://arxiv.org/abs/2504.11729)