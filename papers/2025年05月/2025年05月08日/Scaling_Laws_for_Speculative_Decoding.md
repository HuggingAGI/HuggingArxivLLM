# 推测性解码的扩展定律：探索大规模语言模型的高效推理机制。

发布时间：2025年05月08日

`LLM应用` `人工智能`

> Scaling Laws for Speculative Decoding

# 摘要

> 大型语言模型（LLMs）中对高效解码的需求日益增长，尤其对于 OpenAI-o3 和 DeepSeek-R1 这类依赖于延长链式推理的推理密集型架构而言，这一需求显得尤为重要。本研究通过密集型 LLM 架构探索推测式解码技术，旨在为加速推理任务奠定基础性见解。尽管基于并行草稿-验证循环的推测式解码方法已崭露头角，成为颇具潜力的加速技术，但与通过预训练->SFT->RLHF 训练范式开发的传统骨干 LLM 相比，解码效率的扩展规律仍鲜有研究。在本研究中，我们发现了支配草稿模型接受率（或解码速度）的对数线性扩展规律（定理 1.1、1.2 和 1.3），这些规律跨越了三个维度：预训练标记量、草稿模型容量和解码批处理大小。基于这些规律，我们实现了 Scylla，它能够协调多维度扩展，适用于流行 LLM（如 Llama2/3、Qwen2.5）。实证验证表明，与 EAGLE2 相比，Scylla 在温度 T=0 时实现了 1.5-2.2 倍的更高接受率，比 EAGLE3 高出 0.3 倍，尤其在总结和问答任务中达到了峰值性能提升（图 2）。工业级推理引擎部署显示，与 EAGLE2 相比，解码吞吐量提升了 2 倍（表 5），验证了系统化扩展在实现高效 LLM 推理方面的变革潜力。代码将在后续版本中发布。

> The escalating demand for efficient decoding in large language models (LLMs) is particularly critical for reasoning-intensive architectures like OpenAI-o3 and DeepSeek-R1, which depend on extended chain-of-thought reasoning. This study investigates speculative decoding techniques through dense LLM architectures to establish foundational insights for accelerating reasoning tasks. While speculative decoding methods leveraging parallel draft-verification cycles have emerged as promising acceleration techniques, the scaling laws governing decoding efficiency remain under-explored compared to conventional backbone LLMs developed through Pretraining->SFT->RLHF training paradigms. In this work, we discover Log-linear Scaling Laws (Theorem 1.1, 1.2 and 1.3) governing draft model acceptance rate (or decoding speed) across three dimensions: pretraining token volume, draft model capacity, and decoding batch size. Building on these laws, we achieve Scylla, which coordinates multi-dimensional scaling for popular LLMs (Llama2/3, Qwen2.5). Empirical validation shows Scylla achieves 1.5-2.2 higher acceptance rate than EAGLE2 and 0.3 higher than EAGLE3 at temperature T = 0, with peak performance gains on summarization and QA tasks (Figure 2). Industrial inference engine deployments demonstrate 2X decoding throughput improvements over EAGLE2 (Table 5), validating the transformative potential of systematic scaling for efficient LLM inference. Code will be released later.

[Arxiv](https://arxiv.org/abs/2505.07858)