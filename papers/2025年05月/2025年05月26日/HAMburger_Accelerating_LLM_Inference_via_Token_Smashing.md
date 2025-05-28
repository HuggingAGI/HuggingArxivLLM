# HAMburger：加速LLM推理的HAMburger方法——通过令牌粉碎实现性能提升

发布时间：2025年05月26日

`LLM理论` `人工智能` `计算机体系结构`

> HAMburger: Accelerating LLM Inference via Token Smashing

# 摘要

> 随着对高效大型语言模型（LLM）推理需求的不断增长，我们需要从算法、系统和硬件等多个维度进行全面优化。然而，现有方法在生成模式上鲜有根本性突破：每个token仍需经历一次前向计算和一次KV缓存操作。这一模式可能并非最优，因为我们发现，LLMs具备精准识别单个KV缓存容量的自我认知能力，许多token甚至可以在缺乏全局上下文的情况下自信生成。基于这一发现，我们提出了HAMburger——一种分层自回归模型，通过摒弃传统统一的token级计算与存储模式，重新定义了LLM推理过程中的资源分配方式。通过在基础LLM架构中嵌入组合式嵌入器和微步解码器，HAMburger实现了将多个token压缩至一个KV，并在每一步生成多个token的突破。此外，HAMburger还具备推测性解码能力，可对自动生成的token予以信任。这一创新使得KV缓存和前向计算量的增长从与输出长度的线性关系转变为次线性关系，并使其能够根据查询困惑度和输出结构动态调整推理速度。实验结果表明，HAMburger将KV缓存计算量降低了高达2倍，同时实现了2倍的TPS提升，且在短上下文和长上下文任务中均保持了高质量输出。我们的方法成功探索了一种极具挑战性的推理范式，兼顾计算与内存效率，采用了一种与硬件无关的通用设计。

> The growing demand for efficient Large Language Model (LLM) inference requires a holistic optimization on algorithms, systems, and hardware. However, very few works have fundamentally changed the generation pattern: each token needs one forward pass and one KV cache. This can be sub-optimal because we found that LLMs are extremely capable of self-identifying the exact dose of information that a single KV cache can store, and many tokens can be generated confidently without global context. Based on this insight, we introduce HAMburger, a Hierarchically Auto-regressive Model that redefines resource allocation in LLMs by moving beyond uniform computation and storage per token during inference. Stacking a compositional embedder and a micro-step decoder in between a base LLM, HAMburger smashes multiple tokens into a single KV and generates several tokens per step. Additionally, HAMburger functions as a speculative decoding framework where it can blindly trust self-drafted tokens. As a result, HAMburger shifts the growth of KV cache and forward FLOPs from linear to sub-linear with respect to output length, and adjusts its inference speed based on query perplexity and output structure. Extensive evaluations show that HAMburger reduces the KV cache computation by up to 2$\times$ and achieves up to 2$\times$ TPS, while maintaining quality in both short- and long-context tasks. Our method explores an extremely challenging inference regime that requires both computation- and memory-efficiency with a hardware-agnostic design.

[Arxiv](https://arxiv.org/abs/2505.20438)