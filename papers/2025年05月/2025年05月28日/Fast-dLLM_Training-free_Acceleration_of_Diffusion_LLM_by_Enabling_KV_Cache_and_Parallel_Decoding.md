# Fast-dLLM：无训练加速的扩散式 LLM，通过启用 KV 缓存和并行解码实现。

发布时间：2025年05月28日

`LLM应用` `大型语言模型`

> Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding

# 摘要

> 基于扩散的大型语言模型（Diffusion LLMs）在非自回归文本生成领域展现出了显著潜力，同时具备并行解码能力。然而，开源 Diffusion LLMs 的实际推理速度往往不及自回归模型，主要原因在于缺乏键值缓存（KV Cache）以及在同时解码多个令牌时出现的质量下降问题。为解决这一差距，我们提出了一种专为双向扩散模型设计的新型块式近似 KV 缓存机制，支持缓存复用且性能下降可以忽略不计。此外，我们发现并行解码过程中生成质量下降的根本原因是条件独立假设下令牌依赖关系的中断。为此，我们提出了一种基于置信度的并行解码策略，选择性地解码超过置信度阈值的令牌，从而缓解依赖关系的破坏并保持生成质量。在 LLaDA 和 Dream 模型上的实验结果跨越多个 LLM 基准测试，展示了高达 	extbf{27.6$	imes$ 的吞吐量提升}，且准确率损失极小，显著缩小了与自回归模型的性能差距，为 Diffusion LLMs 的实际部署铺平了道路。

> Diffusion-based large language models (Diffusion LLMs) have shown promise for non-autoregressive text generation with parallel decoding capabilities. However, the practical inference speed of open-sourced Diffusion LLMs often lags behind autoregressive models due to the lack of Key-Value (KV) Cache and quality degradation when decoding multiple tokens simultaneously. To bridge this gap, we introduce a novel block-wise approximate KV Cache mechanism tailored for bidirectional diffusion models, enabling cache reuse with negligible performance drop. Additionally, we identify the root cause of generation quality degradation in parallel decoding as the disruption of token dependencies under the conditional independence assumption. To address this, we propose a confidence-aware parallel decoding strategy that selectively decodes tokens exceeding a confidence threshold, mitigating dependency violations and maintaining generation quality. Experimental results on LLaDA and Dream models across multiple LLM benchmarks demonstrate up to \textbf{27.6$\times$ throughput} improvement with minimal accuracy loss, closing the performance gap with autoregressive models and paving the way for practical deployment of Diffusion LLMs.

[Arxiv](https://arxiv.org/abs/2505.22618)